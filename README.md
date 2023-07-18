# ParkingSpace

## Introduction

ParkingSpace is a website built using Flask and Convolutional Neural Networks (CNN) that allows users to detect and determine the availability of parking spaces in a parking lot. The website utilizes image recognition techniques to analyze images of the parking lot and provides information on the number of available parking spaces.

## Prerequisites

To run the ParkingSpace website locally, make sure you have the following dependencies installed:

- Python 3.x
- Flask
- TensorFlow
- Keras
- OpenCV
- Numpy

## Usage

1. Start the Flask development server:
2. Open a web browser and visit the following URL: http://localhost:5000/
   
3. Upload an image of the parking lot using the provided interface.

4. Click on the "Detect Spaces" button to initiate the parking space detection process.

5. Once the detection is complete, the website will display the number of available parking spaces.

## How it Works

1. When an image is uploaded, the Flask server receives the image and stores it temporarily.

2. The server preprocesses the image using OpenCV and converts it into a format suitable for input to the CNN model.

3. The preprocessed image is then passed through the CNN model, which has been trained to detect parking spaces.

4. The CNN model analyzes the image and identifies the parking spaces using its learned features and patterns.

5. The model counts the number of detected parking spaces and returns the count to the Flask server.

6. The Flask server sends the count back to the web interface, where it is displayed to the user.


## Acknowledgements

- The Flask web framework: [Flask](https://flask.palletsprojects.com/)
- Convolutional Neural Networks: [Convolutional Neural Networks](https://en.wikipedia.org/wiki/Convolutional_neural_network)
- TensorFlow: [TensorFlow](https://www.tensorflow.org/)
- Keras: [Keras](https://keras.io/)
- OpenCV: [OpenCV](https://opencv.org/)
- Numpy: [Numpy](https://numpy.org/)


