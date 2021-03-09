# Dog-Breed-Classifier
The dog-breed classifier project is a Capstone Project, part of Udacity Data Scientist Nanodegree. 

**Project Overview**

This project uses Convolutional Neural Networks (CNNs). Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

**Libraries**
Keras
OpenCV
Matplotlib
Numpy

**File descriptions**
dog_app.ipynb: Jupyter notebook containing the algorithm and process used to create it.
dog_app.html: A copy of dog_app.ipynb in html format.
Haarcascades folder: Xml file for use with the OpenCv face detector class.
Images: Images in jpg and jpeg format used to test the algorithm's predictions.
saved_models: contains the models saved during this project

**Downloads:**
Pre-computer bottleneck features for InceptionV3
https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogInceptionV3Data.npz

**Contents**
The project is organized along the following steps:

Intro
Step 0: Import Datasets
Step 1: Detect Humans
Step 2: Detect Dog
Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
Step 5: Write Your Algorithm
Step 6: Test Your Algorithm

**Repository**
The original Udacity project instructions can be found:
https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification

**Findings**
The model accuracy is 77.6316%, ensuring accuracy greater than 60%, proving suitablility for the current problem. The model proposed works as expected, identifying dogs (and breeds) and humans with good accuracy.
Great project to learn how to build a pipeline to process real-world, user-supplied images.
