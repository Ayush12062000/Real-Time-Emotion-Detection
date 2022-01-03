# Real-Time-Emotion-Detection
> Identifying Facial Emotions by detecting faces in real time using web cam.

## Aim of the Project
1. To identify different faces in the frame
2. Identify their expressions
3. Apply ML and DL Models to predict their emotions


Note: Kindly do not push any changes to Main or Master Branch. Create a New Branch and push all the changes to that branch.

Don't forget to create an issue before making a PR.

👉 Repo Link : https://github.com/Ayush12062000/Real-Time-Emotion-Detection.git

## Table of contents
* About Project
* Languages or Frameworks Used
* Setup

## About Project
Facial Emotion Detection is the process of detecting human emotion from facial
expressions. The human brain detects emotions automatically, and software has now
been developed that can recognize emotions as well. 

The Dataset used is already present in Kaggle you can download the
dataset from here - https://www.kaggle.com/deadskull7/fer2013 , It
contains 48*48 px grayscale images. There are 7 classes/categories in this
dataset (0=angry, 1=disgust, 2=fear, 3=happy, 4=sad, 5=surprise,
6=neutral). Then, I Build the model with three convolution layers. And
used Opencv to detect emotions in Real Time.

## Languages or Frameworks Used
* Python: language
* NumPy: library for numerical calculations
* Pandas: library for data manipulation and analysis
* Tensorflow: library for large numerical computations without keeping deep learning in mind
* Keras: neural network library

## Setup
1. First Clone the repository.
2. Create and activate the virtual environment for the project.
	```	
	$ python -m venv Project_emotion
	$ Project_emotion\Scripts\activate.bat
	```
3. Install the required packages using requirements.txt inside the environemnt using pip.
	```
	$ pip install -r requirements.txt
	```
4. run the Emotion_Detection_1.ipynb in google colab (make sure GPU/TPU is enabled).
5. then, run Real_Time_Detection.py on your local machine.



Refer this for detailed explaination:
👁 https://valueml.com/emotion-detection-using-cnn-in-python-using-keras/


https://user-images.githubusercontent.com/57597700/147909920-b701715d-3a8e-4895-9e59-006bd02a2f7a.mp4


