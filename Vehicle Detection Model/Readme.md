# Vehicle and Non-Vehicle Classification with Neural Networks and OpenCV

This repository contains a machine learning model and an OpenCV script designed to identify vehicles using a webcam. The project leverages a pre-trained Keras model for vehicle detection and OpenCV for capturing video frames from the webcam.

## Model Overview

The model, `keras_model.h5`, is a Keras-based neural network trained to classify images into two categories:
1. Vehicles
2. Non-vehicles

The labels for these categories are stored in `labels.txt`: 
- 0 Vehicles
- 1 Non-vehicles

## Requirements

- Python 3.x
- Keras
- TensorFlow
- OpenCV

You can install the required packages using the following command:

```bash
pip install keras tensorflow opencv-python
```
## Usage

The script openCVpart.py utilizes OpenCV to open the webcam and process the video stream to identify vehicles. Below is a brief explanation of the script:

1. Import Libraries: The necessary libraries are imported, including Keras for loading the model and OpenCV for handling the webcam feed.
2. Load Model: The pre-trained Keras model is loaded.
3. Capture Video: OpenCV is used to start capturing video from the default webcam.
4. Process Frames: Each frame is processed to identify if it contains a vehicle or not.
5. Display Results: The results are displayed on the video feed in real-time.

## Next Steps

As the next step in this project, we aim to use a separate camera to capture image frames via WiFi and process them for vehicle identification. This involves the following tasks:

- Integrate WiFi Camera: Connect and configure a WiFi-enabled camera to the system.
- Capture Frames over WiFi: Modify the script to capture frames from the WiFi camera instead of the default webcam.
- Process and Display: Continue processing the frames using the pre-trained Keras model and display the results in real-time.

---

For any clarification please contact me [Uvindu Kodikara](mailto:uvindukodikara@gmail.com)



