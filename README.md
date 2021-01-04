# Cassava Leaf Disease classification

## Purpose

The purpose of this project is to classify images of cassava leaves into one of 5 categories (4 diseases or healthy leaf).
To accomplish this the following steps have been executed:

1. Explanatory Data Analysis
2. Image Augmentation
3. Creating a baseline keras model
4. Creating keras model with callbacks and dropout layers.

## Data set information

The dataset was downloaded from kaggle competition <a href="https://www.kaggle.com/c/cassava-leaf-disease-classification/overview">Cassava Leaf Disease Classification</a>.
The dataset contains 21 367 labeled images of cassava leafs. Because of performance for my analysis half of the pictures was selected randomly.

## Analysis

The file `image-classification-keras.ipynb` contains the main jupyter notebook with the whole preprocessing and modelling process.

The analysis was performed in Jupyter Notebooks using libraries such as: numpy, pandas, matplotlib, cv2, keras.
