# Sentiment_Analysis
 Automatically classifies the reviews on amazon products as positive or negative comments using machine learning approach.
 
This project is a part of a graduate course on Machine Learning from MIT offered on edx (MIT 6.86x: Machine Learning with python: From Linear Models to Deep Learning). Here, customs functions have been built for implementing different learning algorithms and their accuracy have been tested in the large margin classifier to predict either positve or negative reviews using the bag of words(BOW) approach.

## Project description
<img src = "images/img1.PNG">

There are 4 python files in this project:

## project1.py
This file contains all the custom definition of the functions used to classify the reviews. It includes:
 i. Hinge loss implementation
 ii. Perceptron algorithm implementation
 iii. Average perceptron algorithm implementation
 iv. Pegasos algorithm implementation
 v. Large margin classifier algorithm implementation
*Note:* The average perceptron is just a simple modification of the perceptron algorithm and includes the average of all the parameters across nT steps and pegasos algorithm is implemented by incorporating the bias term in the following pseudo-algorithm.
<img src = "img2.PNG", width = 200, height = 100>

## main.py
This file contains the methods to call the written function and produce outputs.
## utils.py
This file contains the utility functions to process and prepare dataset.
## test.py
This file contains test data to test the implementation of the functions.
