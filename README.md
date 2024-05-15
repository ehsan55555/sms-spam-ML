# SMS Spam Detection Project

This project focuses on developing a machine learning model to accurately classify SMS messages as spam (unwanted messages) or ham (legitimate messages). The goal is to enhance user experience and security by effectively identifying and filtering out spam.

## Project Overview

In this Jupyter Notebook, a model is developed to classify email messages into two categories:
- **Legitimate Emails (commonly referred to as 'Ham')**: These are emails that the user has explicitly or implicitly indicated they wish to receive. They include personal communications, business correspondences, and subscribed newsletters.
- **Spam Emails (commonly known as 'Spam')**: These are unsolicited emails often sent in bulk. They range from benign advertisements to malicious emails containing scams or malware.

The goal is to accurately identify and filter out Spam emails to improve user experience and enhance security.

## Objectives

- Perform exploratory data analysis.
- Prepare the dataset through preprocessing and feature engineering.
- Build a logistic regression model to classify messages.
- Evaluate the model using accuracy, precision, recall, and F1-score.
- Improve the model with cross-validation and parameter tuning.

## Project Structure

1. **Data Import and Initial Exploration**
    - Load the dataset
    - Inspect data types and missing values

2. **Data Cleaning**
    - Remove unnecessary columns
    - Handle missing values

3. **Exploratory Data Analysis**
    - Analyze the distribution of message lengths
    - Visualize the count of spam vs. ham messages

4. **Feature Engineering**
    - Apply TF-IDF Vectorization

5. **Model Training**
    - Split the data into training and testing sets
    - Train a Logistic Regression model

6. **Model Evaluation**
    - Evaluate the model's performance
    - Analyze the confusion matrix and classification report

7. **Model Improvement**
    - Perform cross-validation
    - Tune model parameters using Grid Search

8. **Feature Analysis**
    - Identify influential features for spam detection

9. **Error Analysis**
    - Examine false positives and false negatives

