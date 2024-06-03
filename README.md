# COVID Chest X-Ray Classification using CNN

Welcome to the **COVID Chest X-Ray Classification** project by Brain Mentors. This project demonstrates the implementation of a Convolutional Neural Network (CNN) using the TensorFlow framework to classify chest X-ray images for COVID-19 detection. The dataset used for this project is sourced from Kaggle.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Notebooks](#notebooks)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Application](#application)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The COVID-19 pandemic has created an urgent need for effective diagnostic tools. This project aims to classify chest X-ray images into COVID-19 positive and negative cases using a CNN model. The project leverages TensorFlow for building and training the model and includes comprehensive Jupyter notebooks to explain each step of the process.

## Project Structure
├── ANN_Introduction.ipynb
├── ActivationFunctions.ipynb
├── CovidCNN_XrayClassification.ipynb
├── Madedata1.csv
├── covidApp.zip
├── README.md


- `ANN_Introduction.ipynb`: Introduction to Artificial Neural Networks (ANNs).
- `ActivationFunctions.ipynb`: Explanation and implementation of various activation functions used in neural networks.
- `CovidCNN_XrayClassification.ipynb`: The main notebook for COVID-19 chest X-ray classification using CNN.
- `Madedata1.csv`: Preprocessed dataset used in the project.
- `covidApp.zip`: Source code for the web application developed for deploying the model.

## Dataset

The dataset used for this project is sourced from Kaggle. It contains chest X-ray images categorized as COVID-19 positive and negative. The dataset is preprocessed and saved as `Madedata1.csv`.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/covid-chest-xray-classification.git
    cd covid-chest-xray-classification
    ```

2. **Install the required packages:**

3. **Run the notebooks:**
    Launch Jupyter Notebook and open the provided notebooks to understand the implementation details.

## Notebooks

- **ANN_Introduction.ipynb**: This notebook provides an introduction to Artificial Neural Networks, explaining their structure and how they work.
- **ActivationFunctions.ipynb**: This notebook covers different activation functions such as Sigmoid, Tanh, and ReLU, and their role in neural networks.
- **CovidCNN_XrayClassification.ipynb**: This is the main notebook where the CNN model is built, trained, and evaluated on the chest X-ray dataset.

## Model Training and Evaluation

The CNN model is trained using the TensorFlow framework. The training process, along with model evaluation metrics such as accuracy, precision, and recall, is detailed in the `CovidCNN_XrayClassification.ipynb` notebook.

## Application

The `covidApp.zip` file contains the source code for a web application that deploys the trained CNN model. Users can upload chest X-ray images to the app, and it will predict whether the images indicate a COVID-19 infection.


