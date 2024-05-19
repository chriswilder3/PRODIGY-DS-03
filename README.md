# Bank Marketing Campaign Analysis

## Overview

This project is part of the internship program at Prodigy Infotech and focuses on analyzing and predicting the outcomes of a bank marketing campaign dataset obtained from the UCI Machine Learning Repository. The dataset contains various attributes related to customer demographics, contact details, and past campaign interactions. The goal is to build a model to predict whether a customer will subscribe to a term deposit (`y`), using a decision tree classifier.

## Table of Contents

- [Data Loading](#data-loading)
- [Data Preprocessing](#data-preprocessing)
- [Train-Test Split](#train-test-split)
- [Model Training and Evaluation](#model-training-and-evaluation)

## Data Loading

The project starts with loading necessary libraries and importing the dataset using pandas.

```python
import pandas as pd

# Loading the dataset
data = pd.read_csv('bank-full.csv')
```

## Data Exploration 

Explore the relation between age - subscription , income- subscription pairs. Then Implement a Decision Tree classifier on it.
