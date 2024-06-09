# Global Fish Tracking Service (GFTS)

A Destination Earth Platform use case.

## Clone the github repository

To get a local copy of the GFTS repository, you can clone it on your local computer and/or server:

```
git clone https://github.com/destination-earth/DestinE_ESA_GFTS.git
```

## How to run the jupyter notebooks locally?

Jupyter notebooks to showcase GFTS are in the `docs` folder and can be run after installing Python and the required packages listed in the [.binder/environment.yml](https://raw.githubusercontent.com/annefou/DestinE_ESA_GFTS/main/.binder/environment.yml) file.

### Install Python

To install Python, we recommend to install [conda](https://conda.io/projects/conda/en/latest/index.html) or [miniconda](https://docs.anaconda.com/free/miniconda/) and then create a new conda environment using [.binder/environment.yml](https://raw.githubusercontent.com/annefou/DestinE_ESA_GFTS/main/.binder/environment.yml):

```
conda env create -f environment.yml
```

Do not forget to switch to the `gfts` conda environment prior to executing any Jupyter notebooks or programs from the GFTS repository.

```
conda activate gfts
```

To deactivate the `gfts` environment:

```
conda deactivate
```

### Start JupyerLab and run the Jupyter notebooks

Once all the required packages are installed, you can start JupyterLab and run the jupyter notebooks from the `docs` folder:

```
jupyter lab
```

## How to deploy GFTS Hub

Instructions on how to build and deploy GFTS hub are described in [./gfts-track-reconstruction/jupyterhub/README.md](https://github.com/destination-earth/DestinE_ESA_GFTS/blob/main/gfts-track-reconstruction/jupyterhub/README.md).

The current Jupyterhub deployment is done on OVH cloud operator.

## Contributions

Tho contribute to DestinE Open Source SW collections please refer to [Rule of Participation](docs/rule_of_participation.md)

## Code of Conduct

DestinE open source community abide to this [Code of Conduct](docs/code_of_conduct.md)
