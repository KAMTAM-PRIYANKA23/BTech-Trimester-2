# House Price Estimation Using Matrix Multiplication

A Mathematics for AI lab micro-project demonstrating how matrix operations are used to model a neural network for house price estimation.

## Problem Statement

Estimate a house price score using three input features:

- House size (in 100 sq. ft.)
- Distance from the city centre
- Age of the house

## Mathematical Approach

The model uses a neural network with:

- **Input layer:** 3 features
- **Hidden layer:** 2 neurons
- **Output layer:** 1 neuron

The calculations cover:

1. Matrix multiplication of the input vector and weight matrix.
2. Addition of bias values.
3. ReLU activation in the hidden layer.
4. Calculation of the final output using the output-layer weights and bias.

## Python Implementation

The model was implemented using Python and NumPy.

The code includes:
- A ReLU activation function.
- A function to calculate the hidden-layer output.
- A function to calculate the final output layer.
- Step-by-step display of the calculations.

## Result

<escape>Predicted House Price Score: 3.5200</escape>

The result is the model's output score for the given sample input.

## Project Documentation

[View the submitted project PDF](./MAI-Project.pdf)

---

**Course:** Mathematics for AI  
**Session:** 3 - Modelling a Single-Layer Neural Network Using Matrix Multiplication  
**Case Study:** House Price Estimation
