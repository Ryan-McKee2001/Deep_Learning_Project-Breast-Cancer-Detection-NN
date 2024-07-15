# Breast Cancer Diagnosis using Neural Networks

## Project Overview

This project involves constructing and optimizing an artificial neural network to diagnose breast cancer using the Wisconsin dataset. The initial model is evaluated, and enhancements are proposed and implemented to improve classification accuracy and overall model performance.

## Dataset

The Wisconsin Breast Cancer dataset contains 569 observations with 30 features each. It is used to train and evaluate the neural network model.

## Model Architecture

- **Input Layer**: 30 nodes
- **Hidden Layer**: Initially 5 neurons, later increased to 15 neurons
- **Output Layer**: 1 neuron for binary classification
- **Activation Functions**: Initially sigmoid, later changed to ReLU
- **Preprocessing**: Standard normalization applied

## Performance Evaluation

- **5-Fold Cross-Validation**: Used to rotate data subsets for training and validation.
- **Confusion Matrices**: Used to evaluate precision, recall, F1 score, and accuracy.
- **ROC Curve**: Used to assess the model's discriminatory ability.

## Baseline Model

- **Training Accuracy**: 0.728212
- **Testing Accuracy**: 0.732619
- **Training Error**: 0.568751
- **Testing Error**: 0.554755
- **AUC**: 0.5 (indicating poor performance)

## Model Improvements

- **Preprocessing**: Applied standard scaling.
- **Activation Functions**: Changed hidden layer activation from sigmoid to ReLU.
- **Hyperparameters**: Adjusted batch size from 128 to 100 and learning rate from 0.01 to 0.03.
- **Model Complexity**: Increased the number of neurons in the hidden layer from 5 to 15.

## Final Model

- **Training Accuracy**: 0.988577
- **Testing Accuracy**: 0.973622
- **Training Error**: Improved significantly
- **Testing Error**: Improved significantly
- **AUC**: 1 (indicating excellent performance)

## Results

The final model exhibits significant performance improvements across all key metrics, providing a robust classification model for the Wisconsin Breast Cancer dataset.

- **Precision**: 0.977452
- **Recall**: 0.980992
- **F1 Score**: 0.978994
- **Accuracy**: 0.973622
- **AUC**: 1

## Conclusion

Through systematic evaluation and enhancement, the neural network model for diagnosing breast cancer was significantly improved. The final model demonstrates excellent performance and provides a feasible solution for classifying the Wisconsin Breast Cancer dataset.

## Acknowledgments

- **CSC3066 – Deep Learning**: Course for which this project was developed.
- **Wisconsin Dataset**: Source of the data used in this project.
