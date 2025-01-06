# Face-Detection-and-Recognition-For-Movie-Scenes

## Overview

This project is focused on automating the process of detecting and recognizing faces from movie scenes for a movie streaming application. The company aims to display cast and crew details when users pause a movie and click on the cast information button. The project consists of three main parts:

### **Part A: Face Detection System**
The goal of this part is to build a face detection system that identifies and masks faces in movie scene screenshots.

### **Part B: Image Dataset Creation**
The second part involves creating an image dataset that the AI team can use to build a facial recognition model. This dataset contains images of individuals and will be labeled for face recognition tasks.

### **Part C: Face Recognition System**
This part focuses on recognizing individuals from facial images. The dataset consists of 10,770 images of 100 individuals, which are used to train and test the recognition system.

## Objectives

- **Part A**: Build a face detection system capable of detecting faces in screenshots of movie scenes.
- **Part B**: Create a facial image dataset, including metadata extraction and dataset preparation.
- **Part C**: Implement a face recognition system to recognize and label individuals in images.

## Dataset

### **Part A: Face Detection Data**
The dataset for Part A includes images with the following attributes:
- **label**: Identifies the object (face) in the image.
- **notes**: Additional comments (currently empty).
- **points**: Coordinates of the face mask (top-left and bottom-right).
- **imageWidth**: Width of the image in pixels.
- **imageHeight**: Height of the image in pixels.

### **Part B: Image Dataset for Classifier**
This dataset consists of facial images containing either multiple individuals or a single individual per image, used for training face recognition models.

### **Part C: Face Recognition Data**
A dataset containing 10,770 images of 100 individuals, collected from Pinterest, used for face recognition tasks.
