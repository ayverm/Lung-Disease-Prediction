# Lung Disease Prediction from Chest X-Ray (CXR) using Convolutional Neural Network

This repository is for our B.Tech major project. This repository contains a Convolutional Neural Network (CNN) model for predicting lung diseases from medical images. The CNN is trained on a labeled dataset of lung images to classify the presence of different lung diseases.

# Table of Contents
1.) Introduction<br>
2.) Dataset<br>
3.) Model Architecture<br>
4.) Training<br>
5.) Result<br>

Introduction<br>
The early detection of lung diseases play a crucial role in improving patient outcomes. This project aims to build a deep learning model based on CNNs that can analyze lung images and predict the presence of various lung diseases, such as pneumonia,lung opacity, covid, and others.

Dataset<br>
The dataset used in this project is COVID-19 Radiography dataset. It includes images of healthy lungs and lungs affected by different diseases. The dataset is divided into training, validation, and test sets to facilitate model training, evaluation, and testing.

<b>Model Architecture<br>
The CNN model architecture used for this project is designed to efficiently process lung images and perform disease classification. Details about the layers and configuration of the CNN are as given below:<br>

![IMG_20230729_220503_505](https://github.com/ayverm/Lung-Disease-Prediction/assets/91595998/280d342c-27a0-41a8-968c-c3638188e3a2)

Training<br>
The training process involves forward propagation in which the labeled lung image is feeded into the CNN model and then using back propagation the classification error is adjusted.

Result<br>
The result of the model evaluation including accuracy for each class will be displayed. The result will predict whether a person has COVID-19 ,Lung Opacity ,Viral Pneumonia or it is normal from their Chest X-Ray (CXR) scan by image classification using Convolutional Neural Network.

The most important step in any Data Science project is the model deployment. We have a lot of options in python for deploying our model. Some popular frameworks are Flask and Django. But the issue with using these frameworks is that we should have some knowledge of HTML, CSS, and JavaScript. Keeping these prerequisites streamlit was being used for model deployment.<br>

<img width="960" alt="Screenshot 2023-07-30 203200" src="https://github.com/ayverm/Lung-Disease-Prediction/assets/91595998/0c347fd7-8f19-48b4-965f-d6f08d4cb708">


