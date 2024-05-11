# Facial-Emotion-Recognition-in-Humans-
Facial Emotion Recognition: Leveraging CREMA-D Dataset with Convolutional Neural Networks


This project entails implementing a deep learning-based emotion recognition model on the CREMA-D dataset, leveraging facial landmarks and Convolutional Neural Networks (CNN). Through the integration of K-fold cross-validation, the model aims to accurately classify five emotions from video-derived image data. Python is utilized for development, emphasizing the use of CNN for efficient model training and validation.


Libraries utilised in this emotion recognition are:


DeepFace: for facial analysis
OpenCV: for image processing
Numpy: for numerical operations.
Shutil: aids in file manipulation tasks.
Mediapipe: for facial landmark detection
TensorFlow and Keras: for building and training convolutional neural network (CNN) models. 
pickle, glob, and collections: for data handling and manipulation. 


Dataset: 
CREMA-D: stands for Crowd-sourced Emotional Multimodal Actors Dataset. The original CREMA-D dataset includes videos of six different emotions: happiness, sadness neutrality, disgust, fear, and anger. The journey started with the extraction of frames using OpenCV’s ’VideoCapture’ function at a constant 30 frames per second (fps) from the CREMA-D video dataset. The retrieved frames underwent a careful pre-processing routine to guarantee a smooth downstream procedure. This included the crucial operations of cropping and resizing. The use of Facemesh from Mediapipe, which uses facial landmark detection, enhanced the cropping process.This method streamlined focus on key facial emotions while establishing the groundwork for subsequent facial landmark feature extraction.


You can access the CREMA-D dataset through the link given below:


https://github.com/CheyneyComputerScience/CREMA-D
