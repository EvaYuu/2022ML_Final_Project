# 2022ML_Final_Project

This repository is the official implementation of my final project for 111 Fall Introduction to Machine Learning. 

## Training

To train the model in the project, download the data [here](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022) and the train.ipynb python notebook, then upload this directory structure to your google cloud:

/ML_FP

├── train.ipynb

├── data

│   ├── train.csv

│   ├── test.csv

│   ├── sample_submission.csv

Open the train.ipynb with Google Colab and click run all.
Remember to authorize the permission request.

## Evaluation

To reproduce the result, do the same thing as training step, furthermore download the inference.ipynb and the pre-trained model from link below:

/ML_FP

├── train.ipynb

├── inference.ipynb

├── my_model.h5

├── data

│   ├── train.csv

│   ├── test.csv

│   ├── sample_submission.csv


## Pre-trained Models

You can download pretrained models here:

- [my_model](https://drive.google.com/file/d/18XXkCIONt1s5c5Xkpdx0VH5Uqfrd5CLt/view?usp=share_link) 

## Results

Our model achieves the following performance on :

### [Tabular Playground Series Aug-2022 on kaggle](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022)

| Model name         | Private Score   | Public Score   |
| ------------------ |---------------- | -------------- |
| my_model           |     0.59102     |    0.58431     |
