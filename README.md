# Image Classifcation using Deep Learning with Support Vector Machines

## Description

With the immense usage of smart phones in developed countries, people are sharing information via various types of messenger applications in unimaginable volumes. A natural and unfortunate consequence of this is message abuse in written and visual form with written texts and images. In this project we aim to partially tackle this societal issue using deep learning with SVC.

The idea is to develop and train a smart algorithm that takes an image from a message as input and detects if the image contains nudity or not. That is, the algorithm will classify the picture as ”Nude” or ”Safe”. The receiver of the picture will have the chance to either block or open the message; having seen the class of the newly arrived image. The goal of this application is to reduce message harassment and prevent unwanted information sharing.

## Results

The final model architecture of our CNN achieves 81% accuracy and 81% recall. That is, it has a high true positive ratio: if a picture is false classified, there is an 80% probability that this picture will be classified as Nude.


## Exploring Data

I have provided a few sample data to confirm correctness of the training set. In particular, the ”Nude” dataset will consist of pictures the expose a lot of skin for both women and men of all races, and similarly, the ”Safe” dataset will consist of pictures of both women and men of all races that do not reveal a lot of skin, but instead wearing clothes.


## Software Requirements

- anaconda3 installation for python 3.2

- tensorflow python libraries


## Creating an app: requirements

- A clone of [TensorFlow (0.9)](https://github.com/tensorflow/tensorflow)

- TensorFlow building locally. [Instructions](https://www.tensorflow.org/versions/r0.9/get_started/os_setup.html#download-and-setup)

- An android device setup to allow application installations via adb. [Instructions](https://developer.android.com/studio/command-line/adb.html)
