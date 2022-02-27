# **Dog Breed Identification** *using Deep Learning*

## Problem Description:
 * Who's a good dog? Who likes ear scratches? Well, it seems those fancy deep neural networks don't have all the answers. However, maybe they can answer that ubiquitous question we all ask when meeting a four-legged stranger: what kind of good pup is that?

* With 120 breeds of dogs and a limited number training images per class, you might find the problem more, err, ruff than you anticipated.

## Data:
 *  A training set and a test set of images of dogs. Each image has a filename that is its unique id. The dataset comprises 120 breeds of dogs. The goal of the project is to create a classifier capable of determining a dog's breed from a photo.

*Dataset from Kaggle: https://www.kaggle.com/c/dog-breed-identification/data*

## Evaluation:
  * This project is evaluated on Multi Class Log Loss between the predicted probability and the observed target.

## Model:
  * Model from Tensorflow Hub. 

  * Model URL: https://tfhub.dev/google/tf2-preview/mobilenet_v2/classification/4
  * About Model: This TF-Hub module uses the TF-Slim implementation of mobilenet_v2 with a depth multiplier of 1.0 and an input size of 224x224 pixels.

  The module contains a trained instance of the network, packaged to do the image classification that the network was trained on. If you merely want to transform images into feature vectors, use module google/tf2-preview/mobilenet_v2/feature_vector/4 instead, and save the space occupied by the classification layer.

## Model Accuracy: 99.83%

## Some of the custom predictions:
* ![image](https://user-images.githubusercontent.com/63797339/155894360-40761ff4-817c-4b35-bd71-8c23dbc91b83.png)
* ![image](https://user-images.githubusercontent.com/63797339/155894371-b66b28f5-8b2a-434a-8e1c-54f6d9a39ce1.png)
* ![image](https://user-images.githubusercontent.com/63797339/155894383-e6a4290d-ee8c-4cf4-9999-732cee6365ac.png)

** This project is done with the help of Daniel Bourke and Andrei Neagoie from the course "Complete Machine Learning & Data Science Bootcamp 2022"
*Link to the course: https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/
