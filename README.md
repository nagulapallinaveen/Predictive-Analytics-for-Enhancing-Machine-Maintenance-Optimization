# Predictive-Analytics-for-Enhancing-Machine-Maintenance-Optimization

## Team Overview
- **Penchala Akshay Kumar Kandagaddala**
- **Yogesh Savirigana**
- **Venkata Satya Naveen Nagulapalli**
- **Shashank Rao Gujja**
- **Sudeshna Mullaguru**
- **Vijaya Lakshmi Kalpana Potti**

## Business Challenge
The project addresses the critical issue in manufacturing: minimizing unplanned downtime due to equipment failures, which can cause significant financial and operational disruptions.

## Problem Statement
Traditional maintenance practices in manufacturing, often inadequate, lead to excessive downtime and costs. Predictive maintenance (PdM), utilizing data analytics and machine learning, aims to preemptively address equipment failures, thus enhancing efficiency and profitability.

## Dataset Overview
- **Data Source:** UCI Machine Learning Repository ([AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)).
- **Methodology:** Utilize historical data, real-time monitoring, and machine learning algorithms to predict potential failures.
- **Objective:** To shift from reactive to proactive maintenance, identifying failure patterns and anomalies through data analysis.
- **Features:** 14 features, including machine operational parameters like temperature, speed, torque, and tool wear.
- **Targets:** Indicators of machine failure (binary) and failure types.

## Technical Implementation
1. **Data Importing:** Using PySpark for data handling.
2. **Data Cleaning and Preprocessing:** Renaming, type casting, missing value handling, and dropping irrelevant columns.
3. **Data Exploration:** Using SQL queries for insights.
4. **Feature Engineering:** Addressing data imbalance, encoding categorical variables, and feature scaling.
5. **Model Building:** Decision Tree, Random Forest, Linear SVC, and Logistic Regression.
6. **Model Evaluation:** Focusing on metrics like recall, precision, AUC, and confusion matrix to ensure effective prediction of machine failures.

## Conclusion
The Decision Tree model, with its highest recall, emerges as the most suitable for predicting machine failures, crucial in reducing unplanned downtime in manufacturing. Its ability to proactively predict failures aligns well with the goal of optimizing manufacturing efficiency.
