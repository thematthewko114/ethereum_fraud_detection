# Ethereum Fraud Detection with Pytorch
 
## Background info

Hello world!

### Introduction

This is my final-year project as a Computer Engineering student in CUHK, supervised by [Prof. Zili Shao](https://www.cse.cuhk.edu.hk/~shao/) from the [Department of Computer Science and Engineering](https://www.cse.cuhk.edu.hk/).

### Project Objective

To develop efficient and effective Ethereum fraud dection techniques by utilizing AI technology (e.g. Graph Attention Network).

## Installation

1. Using the conda environment manager to run the project script using Jupyter Notebook, install [Anaconda](https://docs.anaconda.com/free/anaconda/install/) first
2. You may use the Navigator or the anaconda prompt to launch Jupyter Notebook (including creating a new environment), I will create a new environment for the project. To run it with the anaconda prompt, run these commands
```
conda create -n <YOUR-ENVIRONMENT-NAME>
conda activate <YOUR-ENVIRONMENT-NAME>
conda install -c anaconda jupyter
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
conda install -c conda-forge scikit-learn pandas matplotlib numpy datetime timezone json
jupyter notebook
```
3. Your browser should be running the notebook if there are no errors
4. Run the project by finding the index.ipynb and run the script.

### Resources
- Dataset selected in this project: https://github.com/salam-ammari/Labeled-Transactions-based-Dataset-of-Ethereum-Network/tree/master
