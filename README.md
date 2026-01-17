\# Class Imbalance Handling using Sampling Techniques



\## 📖 Overview

Class imbalance is a common problem in machine learning where one class significantly outnumbers the other. This leads to biased models that perform poorly on the minority class.  

This project demonstrates the use of \*\*different sampling techniques\*\* to handle class imbalance and evaluates their impact on various \*\*machine learning models\*\*.



---



\## 📊 Dataset

\- \*\*Name:\*\* Credit Card Dataset

\- \*\*Target Variable:\*\* `Class`

&nbsp; - `0` → Non-Fraud

&nbsp; - `1` → Fraud

\- The dataset is highly imbalanced, making it suitable for studying resampling techniques.



---



\## 🧠 Objective

\- Apply different \*\*sampling techniques\*\* to balance the dataset

\- Train multiple \*\*machine learning models\*\*

\- Compare model performance using \*\*accuracy\*\*

\- Identify which sampling technique works best with which model



---



\## 🔄 Sampling Techniques Used

The following sampling methods were applied \*\*only on the training dataset\*\*:



1\. \*\*Random Under Sampling\*\*

2\. \*\*Random Over Sampling\*\*

3\. \*\*SMOTE (Synthetic Minority Over-sampling Technique)\*\*

4\. \*\*ADASYN\*\*

5\. \*\*SMOTE + ENN (Hybrid Sampling)\*\*



---



\## 🤖 Machine Learning Models

Five different machine learning models were trained on each balanced dataset:



\- Logistic Regression

\- Decision Tree Classifier

\- Random Forest Classifier

\- Support Vector Machine (SVM)

\- Naive Bayes



---



\## ⚙️ Methodology

1\. Load and analyze the dataset

2\. Perform train-test split using stratified sampling

3\. Apply sampling techniques on the training data

4\. Train ML models on balanced datasets

5\. Evaluate model performance on original test data

6\. Compare results across different sampling methods



---



\## 📈 Results

The performance of each model was evaluated using \*\*accuracy\*\*.  

A comparison table was created to analyze how different sampling techniques affect different models.



Results are available in:



