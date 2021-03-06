# Dog Breed Classifier in PyTorch
This is a repo for the Dog Breed Classifier Project  in Udacity Nanodegree

It is implemented by using PyTorch library.

**Udacity's original repo is [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)**



# Project Overview:


In this project I have learned how to build a pipeline to process real-world, user-supplied images. Given an image of a dog, my algorithm will identify the resembling dog breed.

Along with exploring state-of-the-art CNN models for classification, a series of models designed to perform various tasks in a data processing pipeline.


## Import Datasets

* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
* Download the [human_dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

## Project steps

Step 0: Import Datasets

Step 1: Detect Humans using OpenCV's implementation of [Haar feature-based cascade classifiers](http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html) to detect human faces in images.

Step 2: Detect Dogs using Pre-trained VGG-16 Model

Step 3: Create a CNN to Classify Dog Breeds (from Scratch)

Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning) using Pre-trained VGG-19 Model

Step 5: Writing the Algorithm

Step 6: Testing the Algorithm
