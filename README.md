# BIO-482 Miniproject :brain: :mouse:	:technologist:	

Repository for the data analysis miniproject of the course _**Neuroscience: cellular and circuit mechanisms**_ (BIO-482), EPFL. 

This repository contains a MATLAB and Python version of this project, as well as associated functions used for computations.

This project is based on the published [dataset of single-cell recordings in awake mice](https://zenodo.org/records/7833080]) previously collected at LSENS, which resulted in the publication: 
[Membrane potential dynamics of excitatory and inhibitory neurons in mouse barrel cortex during active whisker sensing](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0287174). 


**Note: the  `dataviewer.py` script cannot be used currently**.

## Setting up
### Download
- Clone `git clone ...` or download as zip file this repository (green button).
- Download `Data_Bio482.mat` dataset at the provided link.

The repository should contain the following folders:
- `doc`: documentation related to the project and to the data.
- `matlab`: code and helper functions to do the project with MATLAB.
- `python`: code and helper functions to do the project using Python.

**Note**: add the `.mat` file in a `bio482_miniproject/data` folder.

### Installation and usage

1. **If you're using MATLAB**:
  - Add the `/matlab` folder to your MATLAB path to run the code.
  - Make sure you also have installed the following:
    - Signal Processing Toolbox
    - MATLAB Curve Fitting Toolbox
    - Statistics and Machine Learning Toolbox
2. **If you're using Python**:
  - You need to have Anaconda installed for your system: [install anaconda here](https://docs.anaconda.com/anaconda/install/index.html). 
  - Once Anaconda is installed, open a terminal and install a "bio482" conda environment:
           `conda create -n bio482 numpy scipy matplotlib seaborn h5py pandas jupyterlab statsmodels scikit-learn`
  - Close terminal to make the conda environment effective.
  - Make sure the environment is installed. Open a terminal: `conda env list`. The "bio482" environment should be there.

    Then, to work on the project:
  - Go to `python` and open a terminal
  - Activate the environment: `conda activate bio482`.
  - Then run: `jupyter lab`.
  - Open notebooks to start working on the project.

**Note**:
-   <s>To run the `dataviewer.py`, edit the file by replacing the location of `MiniProjectData.mat` to where your current .mat file is (i.e. full path).</s>


    **Note about paths**:
    - **MATLAB**: You must add folders to MATLAB's path: Right-click on folder -> Add to path...
    - **Python**: In jupyter notebooks, you must change paths based on where you cloned this repository.
  
  _fin_ 
 

