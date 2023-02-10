# hand-sign-recognition
A sign language interpreter using live video feed from the camera. 

## Technologies and Tools
* Python 
* TensorFlow
* Keras
* OpenCV

## Setup

* Use comand promt to setup environment by using install_packages.txt and install_packages_gpu.txt files. 
 
`pip3 install -r requirements.txt`

This will help you in installing all the libraries required for the project.

## Process

* Run `collect-data.py` to set the hand histogram for creating gestures. 
* Train the model using Keras by running `train.py`.
* Run `predict.py`. This will open up the gesture recognition window which will use your webcam to interpret the trained Indian Sign Language gestures.
