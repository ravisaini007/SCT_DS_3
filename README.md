# 🏦 Bank Marketing Data Analysis & Decision Tree Classification

An end-to-end data analysis and predictive modeling project on the Bank Marketing Dataset, focusing on customer demographics, campaign features, and their influence on subscription outcomes. The project implements data preprocessing, visualization, and a Decision Tree classifier using Python’s core data science libraries.

## 1.📌 Project Overview

The goal of this project is to analyze the Bank Marketing dataset (UCI repository) and build a Decision Tree model to predict whether a customer will subscribe to a term deposit.
It includes detailed data cleaning, encoding, exploration, and model evaluation to uncover customer patterns that affect campaign success.

## 2.🎯 Objectives

• Understand dataset structure and key customer attributes.

• Handle missing data and encode categorical variables.

• Explore feature relationships through univariate and bivariate analysis.

• Build and train a Decision Tree classifier using entropy-based information gain.

• Evaluate model accuracy, precision, and recall metrics.

• Visualize the tree and interpret decision paths.

## 3.🧰 Tech Stack

Python

• Pandas – Data loading, cleaning, manipulation

• NumPy – Numerical computation

• Matplotlib & Seaborn – Statistical visualization

• Scikit-learn – Model building and evaluation

## 4.🗂️ Dataset

Source: UCI Machine Learning Repository – Bank Marketing Dataset

Features include:
age, job, marital, education, balance, housing, loan, contact, duration, campaign, pdays, previous, poutcome, and y (target).

Target Variable:
y → Whether the client subscribed to a term deposit (yes/no)

## 5.📊 Analysis & Model Workflow

✅ Data Loading and Initial Inspection

🔍 Exploratory Data Analysis (EDA): Distributions of age, job, marital status, balance

🧹 Data Preprocessing: Categorical encoding, train-test split

🌳 Model Building: Decision Tree (criterion = ‘entropy’)

📈 Evaluation: Accuracy = ~90%, Confusion Matrix & Classification Report

🌐 Visualization: Decision Tree structure using plot_tree()

## 6.💡 Key Insights

✅ Majority of customers did not subscribe to term deposits.

✅ Longer call duration strongly correlates with a higher success rate.

✅ Job type and education show significant patterns in conversion rates.

✅ Balance and housing/loan status affect likelihood of subscription.

✅ Decision Tree achieved ~89–90% accuracy, highlighting the dataset’s predictability.

## 7.📈 Business & Analytical Impact

This project demonstrates the ability to:
• Perform end-to-end data preparation and modeling.
• Extract actionable insights from customer data.
• Apply Decision Tree algorithms for interpretable predictions.
• Use Python’s data science libraries for automation and visualization.

## 8.📸 Screenshots / Visuals

![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_3/blob/main/snapshot-1.jpg)
          ![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_3/blob/main/Snapshot-2.png)
          ![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_3/blob/main/Snapshot-3.png)
