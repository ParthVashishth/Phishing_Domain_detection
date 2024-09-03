# Phishing Domain Detection using Machine Learning

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📖 Project Overview

Phishing is one of the most prevalent cyberattacks today, tricking users into revealing sensitive information such as usernames, passwords, and financial data. This project aims to **detect phishing websites** using various **Machine Learning (ML) algorithms**. The model classifies URLs as either **phishing** or **legitimate** based on features extracted from the URLs.

This project is part of my MSc in Computer Forensics and Cybersecurity and compares the effectiveness of several ML models for phishing detection.

## 🚀 Objectives

1. **Data Collection:** Collect a dataset of phishing and legitimate URLs from open-source platforms.
2. **Feature Extraction:** Extract 30 URL-based features to train and evaluate ML models.
3. **Model Training:** Train various supervised ML algorithms, including:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Support Vector Machines (SVM)
   - Decision Trees
   - Random Forest
   - Gradient Boosting
4. **Model Evaluation:** Evaluate models based on accuracy, precision, recall, and F1-score, identifying the most effective model for phishing detection.

## 📊 Dataset

The dataset was collected from publicly available sources like [Kaggle](https://www.kaggle.com/datasets/eswarchandt/phishing-website-detector) and [PhishTank](https://www.phishtank.com/). It contains over **11,000 URLs** labeled as:
- `1`: Phishing
- `0`: Suspicious
- `-1`: Legitimate

## 🔧 Features

We extracted 30 URL-based features from the dataset, including:
- URL length
- Use of IP address
- Presence of `@` symbol
- Number of subdomains
- HTTPS status, and more.

## ⚙️ Machine Learning Models

We implemented and compared several supervised learning models for phishing detection:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Support Vector Machine (SVM)**
4. **Naïve Bayes**
5. **Decision Trees**
6. **Random Forest**
7. **Gradient Boosting**

## 📈 Results

After evaluating the models, **Gradient Boosting** provided the best performance, achieving an accuracy of **97%**, outperforming other models in terms of phishing detection.

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression  | 93%      | 0.93      | 0.93   | 0.93     |
| KNN                 | 96%      | 0.96      | 0.96   | 0.96     |
| SVM                 | 95%      | 0.94      | 0.95   | 0.94     |
| Random Forest       | 96%      | 0.95      | 0.96   | 0.95     |
| Gradient Boosting   | **97%**  | 0.97      | 0.97   | 0.97     |

## 📂 Project Structure

