# Facial Recognition

Quick test of facial recognition functionality that recognizes faces specified by the user in the 'faces' folder in a user taken picture from the default computer webcam.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Setup

What things you need to install the software and how to install them

```
pip install -r requirements.txt
```

Add images to the 'faces' folder as profiles of people you would like the system to be able to recognize. Make sure the file format is either jpg or png.

## Running

A step by step series of examples that tell you how to get a development env running

Change directory to the project directory and run the following command:

```
python FacialRecognition.py
```

A image capturing video will come up. Press space to capture an image and then press escape to use the most recently captured image to find faces in.


## Built With

* [face_recognition](https://pypi.org/project/face_recognition/) - Recognize faces from Python or from the command line
* [OpenCV](https://pypi.org/project/opencv-python/) - Wrapper package for OpenCV python bindings


## Acknowledgments

* [Tech With Tim](https://techwithtim.net/)
