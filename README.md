# Logistic Regression - Social Network Ads

This project demonstrates how to build a logistic regression model to predict whether a user will purchase a product based on their age and estimated salary using the Social Network Ads dataset.

---

## 📌 Project Overview

The goal of this project is to:

- Apply logistic regression for binary classification.
- Understand the relationship between social network users and their purchase behavior.
- Visualize data and model performance using tools like Seaborn, Matplotlib, and ROC curves.
- Evaluate model performance using metrics like confusion matrix, classification report, and accuracy score.

---

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Sweetviz (for automated EDA)

---

## 📂 Files Included

- `SocialNetworkAds_Logistic_Regression.ipynb`: Main notebook containing all steps from data loading to model evaluation.
- `Social_Network_Ads.csv`: Dataset used for training and testing.
- `Sweetviz_Report.html`: Auto-generated EDA report using Sweetviz.

---

## 🔍 Workflow Summary

1. **Data Loading & Exploration**
   - Load dataset
   - Basic exploration and understanding of features and target

2. **Data Preprocessing**
   - Label Encoding for categorical variables
   - Feature selection
   - Splitting into training and test sets
   - Feature scaling using StandardScaler

3. **Exploratory Data Analysis (EDA)**
   - Univariate and bivariate analysis using histograms, boxplots, and scatter plots
   - Automated EDA with Sweetviz

4. **Model Training**
   - Logistic Regression model using `scikit-learn`
   - Model fitting on the training set

5. **Prediction and Evaluation**
   - Confusion Matrix
   - Classification Report
   - Accuracy Score

6. **Cross Validation**  
   - 5-fold cross-validation (`cv=5`) to evaluate model performance and generalization ability

7. **ROC Curve**
   - Plotting the ROC curve
   - Calculating AUC to evaluate the classifier's performance

---

## 📊 Results

- **Accuracy:** ~88%
- **Precision & Recall:** Good performance on both classes
- **ROC AUC:** Indicates a well-performing model
- **Cross-Validation:** 5-fold CV confirms model consistency

---

## 📁 Dataset Information

The dataset (`Social_Network_Ads.csv`) contains the following columns:

- **User ID** (not used for modeling)
- **Gender**
- **Age**
- **EstimatedSalary**
- **Purchased** (Target: 1 if purchased, 0 otherwise)

---

## 📬 Let's connect!

Feel free to reach out for collaboration, feedback, or just to connect!

- 🔗 [LinkedIn](https://www.linkedin.com/in/rashmi-bhosale-000ba6268/)

---

## ⭐ Acknowledgments

This project is part of a machine learning learning journey using Scikit-learn and real-world datasets.


