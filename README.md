# Diabetes Risk Prediction using Feedforward Neural Network (MLP)

## Project Overview
This project builds a feedforward neural network (Multi-Layer Perceptron – MLP) to predict diabetes risk based on comprehensive health indicators. The task is formulated as a binary classification problem to determine whether an individual has diabetes.

## Dataset Description
- Total samples: 269,131
- Format: CSV
- Features: 21 health indicators
- Target: Diabetes (0 = No, 1 = Yes)

Dataset includes demographics, health measurements (BMI, blood pressure), and behavioral factors.

Dataset link:
https://drive.google.com/drive/folders/1YPTctiMDpNUnGqXGy121sxAMXFmiFlkR?usp=share_link

## Model Description
A Multi-Layer Perceptron (MLP) neural network is implemented with:
- Input layer matching health indicators
- Multiple hidden layers with nonlinear activations
- Sigmoid output layer for binary classification

## Optimization Techniques
- Adam optimizer
- Dropout regularization
- Feature scaling
- Early stopping

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The optimized MLP outperforms baseline models such as Logistic Regression.

## Setup Instructions
1. Create virtual environment:
python -m venv venv

2. Activate environment:
source venv/bin/activate (macOS/Linux)
venv\Scripts\activate (Windows)

3. Install dependencies:
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter

## Reproduction Instructions
1. Download dataset and place CSV in project folder
2. Open notebook:
jupyter notebook
3. Run all cells from top to bottom
4. Review results in notebook output

## Project Structure
- diabetes_prediction.ipynb
- README.md
- data/diabetes_data.csv

## Requirements Fulfilled
- Feedforward neural network implemented
- Multiple optimization techniques applied
- Model evaluated with appropriate metrics
- Performance exceeds baseline models
