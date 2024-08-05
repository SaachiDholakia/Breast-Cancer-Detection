# Breast-Cancer-Detection

## MIAS Mammography Final Year Project
This repository contains the code and documentation for the final year project on mammographic image analysis using the MIAS Mammography dataset. As my final year project, I decided to undertake this project to develop and evaluate a deep learning model for detecting and classifying abnormalities in mammographic images.

## Table of Contents
1. Introduction
2. Dataset
3. Installation
4. Model Architecture
5. Results

## Introduction
Breast cancer is a significant health concern, and early detection is crucial for effective treatment. This project utilizes the MIAS Mammography dataset to develop a machine learning model capable of identifying abnormalities in mammographic images. The project focuses on preprocessing the data, building a convolutional neural network (CNN), training the model, and evaluating its performance.

## Team Members
* Saachi Dholakia
* Ayush Gupta
* Pranab Mehrishi
* Kashish Shah

## Dataset
The MIAS Mammography dataset is provided by the Mammographic Image Analysis Society (MIAS). It includes mammographic images categorized by different types of abnormalities, such as calcifications, masses, and architectural distortions.

## Dataset Link
Installation
To run the code in this repository, you need to have Python installed along with the required libraries. You can install the necessary dependencies using pip.

## Model Architecture
The model used in this project is a convolutional neural network (CNN) designed for image classification tasks. The architecture includes:

Convolutional layers for feature extraction.
Fully connected (dense) layers for classification.
Activation functions such as ReLU and softmax.
The model leverages pre-trained weights from models like VGG, fine-tuned on the MIAS dataset.

## Results
The model's performance is evaluated using metrics such as the ROC curve and AUC (Area Under Curve). The results demonstrate the model's ability to distinguish between different types of abnormalities in mammographic images.
