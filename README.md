# Advanced Fault Analysis using Artificial Neural Network (ANN)

A machine learning project focused on developing an artificial neural network (ANN) for efficient fault detection and classification in power distribution systems. The model is designed to accurately identify 12 different fault types using MATLAB/Simulink for simulation and TensorFlow/Keras for the neural network implementation.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project aims to develop an advanced ANN to classify various fault types in power distribution feeders. The model achieved a classification accuracy of 92% across 12 fault types, with a strong focus on minimizing misclassifications and enhancing fault diagnosis capabilities.

## Features
- Fault classification with 12 different conditions, including single line-to-ground, line-to-line, double line-to-ground, and three-phase faults.
- High accuracy of 92% across all fault types.
- Extensive performance analysis, highlighting areas for improvement.

## Technologies Used
- **Python**: Core programming language
- **TensorFlow/Keras**: For building and training the ANN
- **NumPy**: For numerical computations
- **Scikit-learn**: For data preprocessing and model evaluation
- **MATLAB/Simulink**: For power system simulation and generating training data

## Dataset
The dataset used for training and evaluating the ANN consists of simulated fault data generated using MATLAB/Simulink. The data includes various fault conditions and their corresponding three-phase current measurements.

## Model Architecture
- **Input Layer**: 6 neurons (representing the number of input features)
- **First Hidden Layer**: 64 neurons with ReLU activation
- **Second Hidden Layer**: 32 neurons with ReLU activation
- **Output Layer**: 12 neurons with softmax activation (for 12-class classification)

## Results
The model demonstrated:
- **Overall Accuracy**: 92% in classifying fault types
- **Perfect Classification**: For classes 0-5, 7, and 9 with an F1-score of 1.00
- **Very Good Performance**: For classes 6 and 8 with F1-scores of 0.99
- **Areas of Improvement**: For classes 10 and 11 with F1-scores around 0.50

## Setup and Installation
To set up the environment for running the project, follow these steps:
Clone the repository:
   git clone https://github.com/Honey1315/Fault_Classification_ANN.git
Navigate to the project directory
Install the required dependencies
