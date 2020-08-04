# Face Unlock For Linux Based Systems

## Introduction
We can lock and unlock our Linux based systems using face recognition technology for improved security. 


## Requirements

Install below the required libraries on your local machine:

* Python 3.7
* OpenCV 4.1.0
* Numpy 
* Face_recognition

## Commands

* sudo apt-get install gnome-screensaver
* sudo apt-get install xdotool

## Quick Start

I have used three python files to implement the face recognition based unlock system, which are as follows:

1) **face_generate.py**
 This code will detect your face and save it as a sub-folder with your entered name within the 'dataset' folder. These will be 50 images captured by the code as a training dataset for face_train.py code.
 
2) **face_train.py**
 This code will open the dataset folder and take your image from that and train your face using the K-nearest neighbor algorithm and face_recognition library.
 
3) **face_unlock.py**
 This is an important python file that will detect your face using the webcam and unlock the system.

