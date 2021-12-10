## IMaging-PsychiAtry Challenge (IMPAC): Predicting neurodevelopmental disorders from MRI data

## Data
We merged two preprocessed with FreeSurfer datasets:
* The Autism Brain Imaging Data Exchange ([ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)) 
* Attention Deficit Hyperactivity Disorder ([ADHD-200](http://fcon_1000.projects.nitrc.org/indi/adhd200/)) 

And indicated neurodevelopmental disorders in feature `fx` as 0 for control and 1 for diagnosed subjects. 

## Getting started

This starting kit requires Python and the following dependencies:

* `numpy`
* `scipy`
* `pandas`
* `scikit-learn`
* `matplolib`
* `seaborn`
* `nilearn`
* `jupyter`
* `ramp-workflow`

Therefore, we advise you to install [Anaconda
distribution](https://www.anaconda.com/download/) which include almost all
dependencies.

Execute the jupyter notebook, from the root directory using:

```
jupyter notebook neurodevelop_starting_kit.ipynb
```


## Install using `conda` 

We provide an `environment.yml` file which can be used with `conda` to
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
