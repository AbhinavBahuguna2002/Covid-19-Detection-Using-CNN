<h1 align="center">Covid-19 Detection using CNN</h1>

<p align="center">A Convolutional Neural Network (CNN) based project for classifying chest X-Rays as Covid-19 positive or negative.</p>

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Usage](#usage)

## Introduction
This project aims to develop a model using Convolutional Neural Networks (CNN) to detect Covid-19 from chest X-Rays. The model is trained on a labeled dataset of chest X-Rays that are categorized as positive for Covid-19 or negative for Covid-19. The trained model can be used to classify new chest X-Rays and assist medical professionals in identifying potential Covid-19 cases.

## Technologies Used
- Python
- TensorFlow
- Keras
- Flask

## Getting Started
To set up this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/Covid-19-Detection-using-CNN.git`
2. Navigate to the project directory: `cd Covid-19-Detection-using-CNN`
3. Make sure you have installed the required dependencies. 

## Dataset
The dataset used for training the model can be found [here](https://www.kaggle.com/datasets/mr3suvhro/covid-19-xray-image-dataset-with-huge-samples). It consists of labeled chest X-Rays in two categories: Covid-19 positive and Covid-19 negative.

## Model Training
The CNN model is trained on the dataset using Google Colab. The code for model training can be found in the `train_model.ipynb` notebook. The trained model is then saved as `my_model.h5`.


## Usage
1. Start the Flask web application: `python app.py`
2. Access the web application at `http://localhost:5000` in your web browser.
3. Upload a chest X-Ray image to the web application and click on the "Predict!" button.
4. The model will classify the X-Ray as Covid-19 positive or negative and display the result on the web page.
