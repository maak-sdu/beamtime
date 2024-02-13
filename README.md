# beamtime: a repository for working with beamtime data
In this repository, you will find several tools for x-ray scattering data  
collected during synchrotron beamtimes.  
All tools are Python-based and available as iPython notebooks (`.ipynb` files).

## General tools for powder x-ray diffraction and total scattering
Some general tools for powder x-ray diffraction (pxrd) and x-ray total  
scattering (xts) data:
- calibration and azimuthal integration of *ex situ* data.
- calibration and azimuthal integration of *in situ*/*operando* data, including
    - scaling to account for x-ray intensity fluctutations.
    - background-subtraction.
- various plotting tools (line plots, overview plots, etc.).

## Beamline-specific tools
Some of the tools available in this repo are highly specific to experiments  
conducted in the Ravnsbæk Group, Aarhus University (previously University of  
Southern Denmark). 

### P02.1, PETRA III, DESY:
- merging subframes from P02.1, PETRA III, DESY.

### DanMAX, MAX IV:
- extrating .tif images from .h5 files from DanMAX, MAX IV.

### Balder, MAX IV:
- sorting, merging, etc., files from Balder, MAX IV.

## Setup and installation
The following setup and installation guide is applicable for conda 
distributions, i.e., Anaconda and Miniconda.

If not already created, create a new dedicated conda environment called  
`beamtime_env` with a `Python 3.10` installation from the `conda-forge` channel.
In the `Anaconda Prompt`, type the following:
```
conda create -n beamtime_env -c conda-forge python=3.10
```
Activate the `beamtime_env` conda environment:
```
conda activate beamtime_env
```
Install all the required packages listed in the `requirements.txt` file from the  
`conda-forge` channel:
```
conda install -n beamtime_env -c conda-forge --file requirements.txt
```
To update all installed packages in the `beamtime_env` conda environment:
```
conda update -n beamtime_env -c conda-forge --all
```
