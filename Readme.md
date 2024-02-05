# Analysis of LC-MS data from a Shimadzu system


## Instructions
1. Install [conda/mamba](https://docs.conda.io/en/latest/miniconda.html) or [regular anaconda](https://docs.anaconda.com/anaconda/install/index.html)
```
curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"
bash Miniforge3-$(uname)-$(uname -m).sh
```
2. Clone this project to your computer (e.g. by downloading as zip and extracting or cloning via git)
3. Create and enter a new conda environment with the required python packages by navigating to the local copy (clone) of this repository in a terminal on your computer and type: 
```
mamba env create -f environment.yml
conda activate LCMS-analysis
```
4. Start a jupyter lab instance by typing: 
```
jupyter lab
```
5. Now you can open the Example.ipynb and run through the cells to process and plot my example data

