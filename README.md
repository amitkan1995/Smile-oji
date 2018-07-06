# Smile-oji
Using deep learning to detect smiles.
## Introduction
To detect smiles on pre-recorded video or live cam feed. Using Keras and OpenCV<br>
### Requirements
-> numpy
-> matplotlib
-> openCV
-> sklearn
-> imutils
-> TensorFlow/Theano
-> Keras
-> h5py


### Procedure
1. Gather a dataset of people smiling and not smiling people which is tighly cropped around the face(to remove noise).
2. Train the Convolutional Neural Network using `train_model.py` and your custom data set(the network is designed to handle class imbalance).
3. Run the `detect_smile.py` to start a live video using your webcam, or you can also pass an optional argument to enter the path to a pre-recorded video. 