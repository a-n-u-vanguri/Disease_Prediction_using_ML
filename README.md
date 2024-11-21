# 🌟 Disease Prediction Using Machine Learning 🌟

Welcome to the **Disease Prediction System**! This repository contains a machine learning-based system that predicts diseases based on a set of input symptoms. 🚑💻 The system utilizes three powerful classification models: **Support Vector Machine (SVM)**, **Naive Bayes**, and **Random Forest Classifier**. The final prediction is determined using a **majority voting approach**, combining the predictions of all three models. 🗳️

## 🚀 Project Overview

The goal of this project is to predict potential diseases based on the input symptoms using machine learning algorithms. This project leverages popular classification models in **scikit-learn** to train and evaluate the system. 

### 🔑 Models Used:
- **SVM (Support Vector Machine)**: A robust classifier that performs well on high-dimensional datasets. 🔍
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem, ideal for categorical data. 📊
- **Random Forest Classifier**: An ensemble method that builds multiple decision trees to improve accuracy and reduce overfitting. 🌳

### 💡 Key Features:
- Train models on a labeled dataset containing diseases and their corresponding symptoms.
- Make predictions for diseases based on the input symptoms.
- Combine predictions from SVM, Naive Bayes, and Random Forest using **majority voting**. ✔️
- Visualize the model's performance with **confusion matrices** to better understand the accuracy of predictions. 🔍

## 📊 Dataset

The dataset used in this project is a CSV file containing various diseases and their associated symptoms. Each row corresponds to a unique combination of symptoms and the disease it represents.


The dataset is pre-processed by removing missing values and encoding categorical features, making it ready for training and testing the machine learning models. ⚙️

## 🛠️ Requirements

To run this project, you'll need to install the following Python libraries:

- `numpy` 🍀
- `pandas` 📊
- `scipy` 🧮
- `matplotlib` 📈
- `seaborn` 🎨
- `scikit-learn` 🤖

You can install all the required libraries with the following command:

```bash
pip install numpy pandas scipy matplotlib seaborn scikit-learn
