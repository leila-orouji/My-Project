
# CNN Image Classification 

## Overview
Using CNN to classify a group of images to 3 classes.\n
Data set consists of 300 images for all groups.
Server should load the image uploaded by user. 
Do some image processing.
Model Classification.
Return the result response.


## Goals
The aim of this project is to create a model in which gets images from user and classifys the given image to one of the 3 classes.
We are going to create API for the model based on FastAPI then create a Docker image and Implement CI/CD pipeline.

## Datasets
Dataset includes 100 images for each classes. So, totally we have 300 images.

<img src="Abner.jpg" height=150 width=150 align="left">
<img src="bed.jpg" height=150 width=150>
<img src="sofa.jpg" height=150 width=150>


## Tools
Python, Tensorflow, Keras, FastAPI, Docker, CI/CD

## CNN Model
We are creating a CNN model by 3 conv2D layers, 3 MaxPool layers, Flatten and two Dense layers.
Also used Softmax activation function

## FastAPI
We should have a get command in which allows user to put a URL or path of image to the server.
Then server should read the image file and pass it to the classification model and return the class of the image.
