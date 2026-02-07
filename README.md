# Who-Survived-the-Titanic

## Overview
This project implements a **Neural Network model** to predict which passengers survived the Titanic disaster based on demographic and socioeconomic features. Using the classic Titanic dataset, the notebook explores how different **groups of passengers** (e.g., based on gender, age, class, and family structure) influenced survival outcomes.

The goal is not only prediction accuracy, but also **understanding survival patterns** learned by a neural network.

---

## Project Essence
**Who-Survived-the-Titanic**  
A neural-network–based classification model that learns survival trends from historical passenger data and predicts survival outcomes for unseen passengers.

---

## Dataset
The project uses the standard Titanic datasets:

- `train.csv` – Training data with labels (`Survived`)
- `test.csv` – Test data without labels
- `gender_submission.csv` – Baseline reference submission
- `submission.csv` – Model-generated predictions

### Key Features Used
- Passenger Class (`Pclass`)
- Sex
- Age
- Number of siblings/spouses aboard (`SibSp`)
- Number of parents/children aboard (`Parch`)
- Fare
- Embarked port (after preprocessing)

---

## Model
- **Type:** Feedforward Neural Network
- **Task:** Binary classification (Survived vs. Did Not Survive)
- **Framework:** Implemented in Python using common ML/DL libraries
- **Loss Function:** Binary Cross-Entropy
- **Output:** Probability of survival per passenger

The network is trained on the labeled training set and evaluated through predictions on the test set.

---

## Workflow
1. Load and inspect Titanic datasets  
2. Data cleaning and preprocessing  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize numerical features  
3. Define neural network architecture  
4. Train the model on training data  
5. Generate survival predictions  
6. Export predictions to `submission.csv`

---

## Results
The trained neural network captures well-known Titanic survival patterns, such as:
- Higher survival rates among women
- Higher survival rates in upper passenger classes
- Strong influence of age and family size

Predictions are formatted for direct submission to Kaggle-style evaluation systems.

---

## How to Run
1. Open the files: 

NN_Model_for_Who_Survived_The_Titanic.ipynb

train.csv

test.csv

gender_submission.csv

submission.csv





This notebook serves as:

A learning exercise in neural-network–based classification

A demonstration of applying deep learning to structured/tabular data

A practical exploration of historical survival trends using machine learning

Author: Veer Patel
