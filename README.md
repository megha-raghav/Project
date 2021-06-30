# Project
FACE MASK DETECTION

The task is to build a system that can detect whether a person is wearing face mask or not in an given image/real time video stream. It is an object detection and classification problem with 2 different classes(With Mask and Without Mask).

DATASET

To train our model to classify whether a person is wearing a mask or not, we need good dataset with a fair amount of images for both classes. We have taken a Dataset from Kaggle which provide us just what we needed! The dataset contains images of with or without mask.

With_mask : 1914 images
Without_mask: 1917 images


                                   Steps

Phase 1:-Train the face mask detector

Load face mask dataset
Train the face mask classifier with keras/tensorflow.


Phase 2:-Apply face mask detector

Load face mask detector from disk
Detect faces in image and real time video stream.
Apply face mask classifier to determine mask or no-mask
