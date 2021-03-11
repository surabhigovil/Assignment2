# Assignment2: Using AutomL tools on Google Cloud Platform 

In this repository the demo video walks through the process of using AutoMl on Google Cloud Platform(GCP) to automate the task of machine learning.

# Part1:
I have used AutoMl to perform classification task on a tabular data. It is a classification to predict Rain tommorow based on a number of factors.
The dataset used here is publically avaibale on Kaggle: https://www.kaggle.com/jsphyg/weather-dataset-rattle-package. It is a binary classification task. For the training first created a Google Cloud Platform and added data to it in CSV. The CSV was used to create a dataset and a training pipeline.


# Part2(a):
For the Second part the object is to develop and deploy a model on an edge device. Here I have selected to deploy it on an iOS device. To compare and contrast the results from an AutoML trained model, I have trained a Vision model on AutoML and deployed on the edge device. The results show a significant improvement in accuracy from the sample model present in the app to the one trained using AutoML on GCP.  

# Part2(b):
The aim was to create a time series model using BigQuery on GCP. The tutorial points out how SQL like commands can be used to easily develop a model. 
