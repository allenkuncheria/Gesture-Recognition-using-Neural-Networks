# Title
Gesture Recognition Using Neural Networks

# Description
A home electronics company, which manufactures state of the art smart televisions, is looking to develop a feature that recognises five different hand gestures performed by the user via a webcam mounted on the TV, to control it without a remote.

The goal of this deep learning project is to build a neural network that can evaluate the hand gestures and map them to associated commands.

# Project Pipeline
The project is executed as per the following steps:
- Data Reading/Data Understanding
- Data Generator
- Model Building & Training
    - 3D Convolutional Neural Network
    - 2D Convolutional Neural Network + Recurrent Neural Network
- Model Selection

# Results
'Model 7' developed during the project, which is a 2D CNN + RNN model with 1,132,533 parameters, is the best performing model. Early stopping is used to isolate the best weights and the performance parameters are as follows:
- Training loss - 0.66613
- Training accuracy - 0.74702
- Validation loss - 0.66864
- Validation accuracy - 0.78125

Additional details are elaborated in 'Write Up.docx'