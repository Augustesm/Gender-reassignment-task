# Gender Prediction Neural Network

**Gender Prediction Neural Network** is a Python-based machine learning project that demonstrates how to build, train, and evaluate a simple neural network **from scratch**, without using high-level libraries such as TensorFlow or PyTorch. The model predicts the missing gender value of the 5th patient using height and weight as input features.

## Key Features

* 🔢 **Manually implemented neural network**
* 🧠 **Feedforward computation using sigmoid activation**
* 🔄 **Backpropagation algorithm coded from scratch**
* 📉 **Mean squared error (MSE) loss function**
* 🧮 **Gradient descent weight updates**
* 📊 **Training evaluation with multiple hyperparameter configurations**
* 📈 **Prediction of the 5th patient's gender**
* 🔧 **Min–max normalization for feature scaling**
* 🗂️ **Clean comparison table of learning rates and epoch counts**

## Technologies Used

* **Python** — core programming language
* **NumPy** — numerical operations, matrix math, activation functions
* **Pandas** — data loading, preprocessing, tabular results
* **Custom code** — full neural network architecture, forward pass, backpropagation, and gradient updates implemented manually

## Features in Detail

### Neural Network Architecture

* 2 input features: **height** and **weight**
* 1 hidden layer with **two neurons**
* 1 output neuron representing predicted gender probability
* All activation functions use **sigmoid**
* All biases are set to **1**

### Training & Evaluation

* Backpropagation implemented manually
* Multiple experiments performed with different:

  * Learning rates
  * Epoch counts
* A results table summarizes:

  * Final loss
  * Prediction for Patient 5
  * Hyperparameter configuration

### Data Processing

* Dataset constructed from Table 2 (16 patients)
* Gender value of Patient 5 set to unknown
* Features normalized using **min–max scaling**
* The network is trained on the remaining patients, excluding the 5th entry
