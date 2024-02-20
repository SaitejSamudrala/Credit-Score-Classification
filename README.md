# CREDIT SCORE CLASSIFICATION

## Overview

This project aims to use machine learning models to classify the credit score of individuals based on their financial history, demographic information, and other relevant features.

## Dataset

We are using the **Credit Score Classification** dataset from Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/parisrohan/credit-score-classification/).



## Environment

To start off install and setup [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) on your pc.We will be using conda to setup the virtual environment for the entire project to manage all your project dependencies.
After installation navigate to the directory where your cloned repo is located.

###### Run the following command to create a virtual environment

`conda create -p <name_of_your_env> python==3.11.7 -y`

After creation run the following command to activate the environment.

`conda activate <name_of_your_env>`

To install all the required dependencies run the following command.

`conda install --file requirements.txt`

### Note:
To add a new package to the project use the command.

`conda install package_name`

After adding the package run the following command to append the new package to "**requirements.txt**".

`conda list --export | grep -v '^#' > requirements.txt`






