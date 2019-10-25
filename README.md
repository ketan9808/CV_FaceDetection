# CV_FaceDetectionn

## overview
face detection is widely used nowadays. so these program illustrade a basic techinque to detect faces.


## HaarCascade vs HOG vs CNN
the haarcascade classifier is average in case of speed and accuracy as compared to HOG(Histogram of oriented gradient) and CNN(Convolution Neural Network).the HOG is fastest in terms of speed but is less accurate and CNN is more accurate out of 3 but take more time to detect faces.

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

##  HOG
yet to upload the code

## MTCNN
Multi-Task Convolution Neural Network, This is a CNN based model which is used to detect face. along with the face this model is also used to detect various face landmarks like nose, mouth, eyes and confidence.
The program named Face_detection_MTCNN.ipyng illustrate the purpose of the same. The program first capture the image from the cront camera of your computer and then use mtcnn to detect the face and its landmarks and draw them on the frame.
one of the sample output is saved in the repository itself named "MTCHH_OP_0.jpg"

## face detection and music player
This program uses cascade classifier to detect faces and play music whenever any face is detected in frame and when the face goes out of frame the music stops.
