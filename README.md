# Longterm Recurrent Neural Network for Human Action Recognition (LRCN)
# Python Notebooks for UCF50 Dataset

## Table of Contents
### Project Description
### Installation
### Usage
### Note

## Project Description
This project contains four Python notebooks that have been uploaded to the current folder. These notebooks contain all of the required code for training and evaluating models on the UCF50 dataset. One notebook is for a 2D_CNN model that takes action bank features as input, and the other three notebooks are for different variations of the LSTM model.

## Installation
To execute these notebooks, one should install Python Anaconda on their local system or use an online Python environment, preferably Google Colab.

## Usage
To use these notebooks, follow these steps:

- Load the Python notebook in the corresponding Python environment.
- Update the `DATASET_PATH` variable so that it points towards the dataset folder.
- Change runtime type to enable GPU usage. (For Google Colab)
- Run each cell one by one.

First of all, data will be prepared programmatically into a specific format so that it can be fed to the model. Afterwards, the model will take some time for training and evaluation. Corresponding graphs and accuracies will be printed once the model completes its training.

## Note
One can change the `ALL_CLASSES` variable to control the number of classes that are fed to the model.
