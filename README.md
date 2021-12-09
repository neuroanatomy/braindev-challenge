## IMaging-PsychiAtry Challenge (IMPAC): Predicting neurodevelopmental disorders from MRI data

## Data
We merged two preprocessed datasets:
* The Autism Brain Imaging Data Exchange (ABIDE) 
* Attention Deficit Hyperactivity Disorder (ADHD-200) 

And indicated neurodevelopmental disorders in feature `fx` as 0 for control and 1 for diagnosed subjects. 

## Getting started

This starting kit requires Python and the following dependencies:

* `numpy<1.20`
* `scipy`
* `pandas>=0.21`
* `scikit-learn>=0.19,<=0.21`
* `matplolib`
* `seaborn`
* `nilearn`
* `jupyter`
* `ramp-workflow==0.2.1`

Therefore, we advise you to install [Anaconda
distribution](https://www.anaconda.com/download/) which include almost all
dependencies.

Only `nilearn` and `ramp-workflow` are not included by default in the Anaconda
distribution. They will be installed from the execution of the notebook.

Execute the jupyter notebook, from the root directory using:

```
jupyter notebook neurodevelop_starting_kit.ipynb
```


## Advanced install using `conda` (optional)

We provide both an `environment.yml` file which can be used with `conda` to
create a clean environment and install the necessary dependencies.

```
conda env create -f environment.yml
```

Then, you can activate the environment using:

```
conda activate neurodevelop
```

for Linux and MacOS. In Windows, use the following command instead:

```
activate neurodevelop
```
