# Breast Cancer Supervised Learning
## Supervised Learning Experiments on Wisconsin Breast Cancer Dataset

This repository contains various experiments with supervised machine learning models on the Wisconsin Breast Cancer dataset.

### Table of Contents
1. [Introduction](#introduction)
2. [Regression Study](#regression-study)
3. [Classification Study](#classification-study)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

### Introduction

This project aims to explore and analyze the Wisconsin Breast Cancer dataset using different supervised learning techniques. The experiments are divided into two main studies: Regression and Classification.

### Regression Study

In the regression study:
- **Objective**: Investigate how much the **mean radius** feature is affected by other tumor features.
- **Methods**: Two linear regression models were utilized.
- **Approach**: 
  - Evaluate the performance of the two models with different training set sizes.
  - Analyze how the **change in training set size** impacts model performance.

### Classification Study

In the classification study:
- **Objective**: Predict the **diagnosis** (benign or malignant) based on tumor characteristics.
- **Methods**: Five supervised learning algorithms were evaluated.
- **Approach**: 
  - Determine the **outstanding algorithm** for diagnosis prediction.
  - Identify features most associated with the diagnosis of a **malignant mass**.

### Installation

To run the code in this repository, ensure you have the following dependencies installed:

- Python 3.x
- Pandas
- Scikit-learn
- NumPy
- Matplotlib

You can install the required packages using:
```bash
pip install -r requirements.txt
