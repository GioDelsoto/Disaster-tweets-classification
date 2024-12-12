# Tweet Disaster Classification

## Introduction

In this notebook, we will tackle a Kaggle competition aimed at predicting whether tweets are related to disasters. We will start by using two simple techniques: TF-IDF and CountVectorizer, combined with Ridge, Logistic Regression models, and Latent Semantic Analysis (LSA), to create baseline results. The first section focuses on exploring the dataset to gain a deeper understanding of the data. After establishing these baselines, we will move on to a more advanced approach by incorporating the BERT transformer model as a layer in a neural network using TensorFlow.

## Project Structure

The project directory contains the following:

- README.md: This file, providing an overview of the project.

- Notebook file: A Jupyter Notebook (tweet_disaster_classification.ipynb) where all the data analysis, model training, and evaluation steps are implemented.

- Data folder: Contains the dataset used in this project.
- requirements.txt: Contains the libraries used in this project

## Methods Used

- Baseline Models:

  - TF-IDF + Ridge Regression

  - CountVectorizer + Logistic Regression

  - Latent Semantic Analysis (LSA)

- Advanced Model:

  - BERT transformer model as a layer in a neural network using TensorFlow

## Results

Baseline results are obtained using traditional machine learning models and got a F1 score of 0.74

Advanced neural network models with BERT integration aim to improve performance and provide a robust solution for tweet disaster classification, with an amazing F1 score of 0.83
