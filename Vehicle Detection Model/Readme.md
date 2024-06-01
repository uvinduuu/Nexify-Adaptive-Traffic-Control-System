# Vehicle and Non-Vehicle Classification with Neural Networks and OpenCV

This repository contains code for training a neural network to classify images into vehicles and non-vehicles using a custom dataset. It also includes code for using OpenCV to capture images from a webcam and perform real-time classification.

## Steps:

### Dataset Preparation:
- Ensure your dataset is labeled and organized properly with images of vehicles and non-vehicles.
- Preprocess the data by scaling pixel values to the range [0, 1] if needed.

### Model Building:
- Define a neural network architecture using TensorFlow/Keras.
- Compile the model with appropriate loss function, optimizer, and metrics.

### Model Training:
- Train the model on the prepared dataset.
- Monitor training progress and evaluate model performance.
- Save the trained model to a file (`keras_model.h5`).

### Model Evaluation:
- Evaluate the trained model on a test dataset to assess its accuracy.
- Use the saved model for future predictions.

## Real-Time Classification with OpenCV:

### Script: `openCVpart.py`
- Use OpenCV to capture images from a webcam.
- Preprocess the captured images and feed them to the trained model for real-time classification.

---

For any clarification please contact me [Uvindu Kodikara](mailto:uvindukodikara@gmail.com)



