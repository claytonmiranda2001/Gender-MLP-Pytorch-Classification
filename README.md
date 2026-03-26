# Gender Classification with MLP
## Project Objective

This project aims to develop a gender classification model using a Multi-Layer Perceptron (MLP) neural network.
The goal is to classify individuals based on input features using a supervised learning approach.

## Data Preprocessing
* Data cleaning and preparation
* Feature selection
* Train/test split
* Feature scaling using normalization/standardization

These steps ensure the dataset is suitable for training a neural network.

## Model

A Multi-Layer Perceptron (MLP) was used for classification:

* Feedforward neural network
* Hidden layers with nonlinear activation functions
* Optimized using backpropagation
  
## Training Process

* Data split into training and testing sets
* Model trained on labeled data
* Hyperparameters adjusted to improve performance
* Loss Function

The model uses BCEWithLogitsLoss as the loss function, which is suitable for binary classification tasks.
It combines a sigmoid activation with binary cross-entropy in a numerically stable way.

## Model Evaluation

The model was evaluated using classification metrics to measure its performance and generalization:

* Accuracy
  
Training: 96.76%

Validation: 96.95%

Test: 97.09%

* Loss
  
Training: 0.0823

Validation: 0.0820

Test: 0.0773

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* PyTorch
  
## Conclusion

The model achieved high accuracy across all datasets, with very similar results between training, validation, and test sets.
This indicates good generalization and a low level of overfitting.

Additionally, the low loss values reinforce that the model is making confident and consistent predictions.
