# Realtime_Emotion_Detector

# Overview
Realtime Emotion Detection Using Keras

We have created a CNN model using the fer2013.csv dataset from Kaggle's Facial Expression Recognition 
Challenge. The data consists of 48x48 pixel grayscale images of faces. The task is to categorize each face  
based on the emotion shown in the facial expression in to one of seven categories:
(0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

The model is trained for 30 epochs and runs at 63.72 percent accuracy.

# Library Dependencies:
* pip install numpy
* pip install pandas
* pip install tensorflow
* pip install keras
* pip install opencv-python

# Usage:

  

 1. First Set absolute path of fer3.h5, fer3.json, haarcascade_frontalface_default.xml in   
    VideoTester.ipynb  &  fer2013.csv in Emotion_Analysis.ipynb

 
   

 1. Then Run Emotion_Analysis.ipynb

 
   

 1. Then run VideoTester.ipynb

# Acknowledgements:
* http://sefiks.com/2018/01/01/facial-expression-recognition-with-keras/
* https://medium.com/@jsflo.dev/training-a-tensorflow-model-to-recognize-emotions-a20c3bcd6468
