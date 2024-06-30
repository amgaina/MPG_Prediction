# MPG Prediction with Deep Neural Network

## Overview

Welcome to the **Miles Per Gallon (MPG) Prediction Project**! This project aims to predict the MPG of cars based on various features using a Deep Neural Network (DNN). The dataset is sourced from Carnegie Mellon University and includes features such as horsepower, number of cylinders, acceleration, displacement, model year, and origin. Our model achieves an impressive 90% accuracy in predictions.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Project Workflow](#project-workflow)
4. [Dependencies](#dependencies)
5. [Results](#results)


## Introduction

This project is a comprehensive example of how to approach a regression problem using deep learning techniques. We cover the entire process, from data cleaning and preprocessing to model training and evaluation.

## Dataset

The dataset used for this project is from Carnegie Mellon University. It includes the following features:

- **Horsepower**
- **Number of Cylinders**
- **Acceleration**
- **Displacement**
- **Model Year**
- **Origin**

The target variable is **Miles Per Gallon (MPG)**.

## Project Workflow

1. **Data Cleaning**: Handle missing values and correct data types.
2. **Data Normalization**: Scale the data to ensure all features contribute equally to the prediction.
3. **One-Hot Encoding**: Convert categorical features into numerical values.
4. **Model Building**: Construct and train a deep neural network using TensorFlow.
5. **Model Evaluation**: Assess the model's performance and accuracy.

## Dependencies

Ensure you have the following libraries installed:

- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [Pandas](https://pandas.pydata.org/)

You can install these dependencies using `pip`:

```bash
pip install numpy matplotlib tensorflow pandas
```
```bash
git clone https://github.com/yourusername/MPG-Prediction-DNN.git
cd MPG-Prediction-DNN
```
```bash
python MPG_Prediction.py
```
## Result
The model achieves a 90% accuracy in predicting the MPG.

By: Abhishek Amgain
