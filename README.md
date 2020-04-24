# Face Detection

Exploring different techniques used in face detection

## overview

Face detection is widely used nowadays and there are various techniques used to detect faces in pictures. This repository contanin notebooks demonstrating how to these technique works and how you can use them in code.
Currently the repository contain following techniques for Face detection:

- Haarcascade
- HOG
- MTCNN

## Comparision

the haarcascade classifier is average in case of speed and accuracy as compared to HOG(Histogram of oriented gradient) and MTCNN(Convolution Neural Network).the HOG is fastest in terms of speed but is less accurate and MTCNN is more accurate out of 3 but take more time to detect faces.

all of these are implemented in the respective files.

## HaarCascade Classifier

HaarCascade is machine learning model to detect various object. The models are trained using both possitive image(images with faces) and negative image(images without faces). It provide various classifiers for detecting various objects like:

- faces
- eyes
- left eye
- right eye
- eyes with glasses
- full body 
- upper body
- lower body
- smiles
- licence plate

## HOG

yet to upload the code

## MTCNN

Multi-Task Convolution Neural Network, This is a CNN based model which is used to detect face. along with the face this model is also used to detect various face landmarks like nose, mouth, eyes and confidence.
The program named Face_detection_MTCNN.ipyng illustrate the purpose of the same. The program first capture the image from the cront camera of your computer and then use MTCNN to detect the face and its landmarks and draw them on the frame.
one of the sample output is saved in the repository itself named "MTCHH_OP_0.jpg"

## face detection and music player

This program uses cascade classifier to detect faces and play music whenever any face is detected in frame and when the face goes out of frame the music stops.
