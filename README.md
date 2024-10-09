# Diabetes_Prediction_ML

# Diabetes Prediction using Supervised Learning

This project focuses on predicting whether a person has diabetes or not, based on various medical factors. We use machine learning algorithms and evaluate their performance using accuracy and other metrics.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Modeling](#modeling)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This repository contains a supervised machine learning project to predict diabetes in patients. We leverage a variety of features like `Pregnancies`, `Glucose`, `Blood Pressure`, `BMI`, and other medical attributes to train our models.

We will be testing different algorithms like Support Vector Machines (SVM), Logistic Regression, Decision Trees, and others to find the most accurate model.

## Dataset

The dataset used in this project is the **Pima Indians Diabetes Database**. It consists of the following features:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (0 or 1, indicating diabetes status)

The dataset is loaded using `pandas.read_csv()`.

## Installation

To run this project, you need the following dependencies installed:

- Python 3.x
- pandas
- numpy
- scikit-learn
- Jupyter Notebook (optional)

You can install the necessary libraries using the following commands:

```bash
pip install numpy pandas scikit-learn
