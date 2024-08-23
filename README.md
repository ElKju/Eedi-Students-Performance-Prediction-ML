# Student Performance Prediction Using Machine Learning Algorithms

This project involves building and comparing various machine learning models to predict whether a student will correctly answer a specific diagnostic question. The models leverage the student's previous responses and other students' answers to similar questions. Data obtained from Eedi.

## Project Overview

### Machine Learning Models Implemented

- **k-Nearest Neighbors (kNN)**
- **Item-Response Theory (IRT)**
- **Autoencoder Neural Network**
- **Bagged Ensembles**

### Neural Network Enhancements

The neural network model was extended with the following techniques to improve prediction accuracy:

- **L2 Regularization**: To prevent overfitting.
- **Additional Hidden Layers**: For increased model complexity.
- **Dropout**: To randomly drop units during training and prevent overfitting.
- **Activation Functions**: Experimented with different activation functions (ReLU, sigmoid, etc.).

### Variational Autoencoder

A variational autoencoder was also developed as part of the study to explore its effectiveness in the prediction task.

## Performance

- **Best Model Accuracy**: ~70%
  
### Challenges

Despite various techniques applied to enhance model performance, no significant improvements in accuracy were observed beyond ~70%.

### Next Steps

- **Adaptive Boosting (AdaBoost)**: Plan to implement AdaBoost to potentially increase model accuracy.
- **Matrix Factorization**: Explore matrix factorization techniques to improve prediction accuracy.

## Motivation

The ultimate goal of this project is to develop a prediction model that can accurately estimate a student's current ability level. This model can be used to personalize their educational experience by:

- **Customizing Learning Paths**: Automatically recommending topics of appropriate difficulty based on the student's background and learning status.
- **Personalized Education Journey**: Tailoring the learning process to fit each student's unique needs.

