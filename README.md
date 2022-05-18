# Melanoma-Detection-Assignment
> In this assignment, we will build a multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Conclusions
1. The accuracy is increased by **around 20%** (than previous model) and the loss is also gradually decreased.
2. Training Accuracy : 0.7577 <br>
   Validation Accuracy : 0.7255 <br>
   Training Loss : 0.6256 <br>
   Validation Loss : 0.7513 <br>
3. The model is not overfitting anymore after using more data to resolve the issue of class imbalance, a dropout layer and extra epoch(35).
4. To further increase the accuracy, we can tune the model further, add extra layers and increase the epochs.


## Technologies Used
- TensorFlow
- Keras
- Augmentor
- Pandas
- Numpy
- Matplotlib

## Acknowledgements
Give credit here.
This project is developed as part of Exploratory Data Analysis module, Master of Machine Learning and AI, IIIT-Bangalore.


## Contact
Created by [@modaktanaya] - feel free to contact me!
