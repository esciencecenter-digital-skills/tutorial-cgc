# Clustering Geo-data Cubes (CGC) Tutorial

This repository contains notebooks that illustrate how to use CGC, a clustering tool for geo-spatial data. The code is 
hosted on [GitHub](https://github.com/phenology/cgc), and its full documentation is available 
[here](https://cgc.readthedocs.io).

You can run this tutorial in a live JupyterLab session on [mybinder.org](https://mybinder.org) by clicking on the 
following badge:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/escience-academy/tutorial-cgc/main?urlpath=lab/tree/notebooks)

## Notebooks



## Installation

Clone this repository and access its root directory:

```shell script
git clone http://github.com/escience-academy/tutorial-cgc.git
cd tutorial-cgc/
```

In order to run the notebooks, you will need:
* Python 3.6, 3.7 or 3.8;
* Having the following packages installed:
    * CGC (and its dependencies)
    * [Xarray](http://xarray.pydata.org) and [Zarr](https://zarr.readthedocs.io) (to read the example data set)
    * Jupyter

This repository includes a configuration file (`environment.yml`) that allows you to install CGC, Xarray and Zarr
using `conda`:

 ```shell script
conda env create -f environment.yml
```

Activate the `cgc-tutorial` environment:

 ```shell script
conda activate cgc-tutorial
```

### Install Jupyter

Jupyter can be installed using `pip`:

```shell script
pip install jupyter
```

The official Jupyter documentation can be found [here](https://jupyter-notebook-beginner-guide.readthedocs.io).

## Running the Notebooks

From the repository `notebooks` directory, run:

```shell script
jupyter notebook
```

