[//]: # (Image References)


[image1]: ./images/key_pts_example.png "Facial Keypoint Detection"

# Facial Keypoint Detection

This is a Deep Learning Model combined with various other computer vision techniques to detect Facial Keypoints. Facial keypoints include points around the eyes, nose, and mouth on a face and are used in many applications. These applications include: facial tracking, facial pose recognition, facial filters, and emotion recognition. An example is given below.

## Project Overview


![Facial Keypoint Detection][image1]

This project is broken down into three Python notebooks and two Python scripts .

__Notebook 1__    : Loading and Visualizing the Facial Keypoint Data

__data_load.py__  : Loading and Preprocessing the Data 

__model.py__      : Defining the model architecture

__Notebook 2__    : Combining all the parts and training the model to Predict Facial Keypoints

__Notebook 3__    : Facial Keypoint Detection Using Haar Cascades and Trained CNN


The Dataset used for this Project was from [YouTube Faces DB](https://www.cs.tau.ac.il/~wolf/ytfaces/) which contains a total 5770 color images with 68 coordinates for the facial keypoints for each image.


This Project is inspired from the research paper [Facial Key Points Detection using Deep
Convolutional Neural Network - NaimishNet](https://arxiv.org/pdf/1710.00977.pdf) and P1 of [Computer Vision nanodegree at Udacity](https://www.udacity.com/course/computer-vision-nanodegree--nd891).

