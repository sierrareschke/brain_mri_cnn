# Custom Convolutional Neural Network for MRI Classification

## Overview
This repository contains the implementation of a custom convolutional neural network (CNN) designed to classify MRI scans for brain tumor detection (brain.ipynb). The project, conducted in collaboration with the Simulation Engineering Lab, focuses on developing an accurate model using deep learning techniques.

## Project Highlights:
* Objective: Classify MRI scans to detect brain tumors with high accuracy.
* Achieved: 75% accuracy on the validation dataset.

## Technologies & Tools Used:
* Programming Language: Python
* Framework: TensorFlow
* Libraries: Pandas, NumPy, Matplotlib

## Key Features:
#### Data Preprocessing:
* Resizing pixel values, converting images to grayscale, and normalizing data to ensure consistent input for the model.
* Utilized Pandas for efficient data manipulation.
* Applied augmentation techniques using NumPy such as flipping, rotation, zooming, and shifting to enhance dataset diversity.

#### Model Development:
* Developed a CNN architecture using TensorFlow, incorporating various layers and dropout techniques to prevent overfitting.
* Fine-tuned model hyperparameters, including learning rate and batch size, to optimize performance.

#### Visualization:
* Leveraged Matplotlib to visualize training performance metrics like accuracy and loss over epochs, aiding iterative model improvements.


## Results:
Achieved 75% accuracy on the validation dataset, demonstrating the effectiveness of the CNN model in MRI scan classification.


## Skills Demonstrated:
* Python, TensorFlow, NumPy, Pandas, Matplotlib
* Convolutional Neural Networks (CNN)
* Machine Learning Model Creation and Optimization
* Data Processing and Preprocessing
* Visualization of Training Metrics
