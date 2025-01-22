# **Exploring and Predicting Students' Academic Performance Through Personal and Social Attributes**

This repository contains the final report of my Data Science project where I predictED student final grades using various statistical and machine learning models. The analysis focuses on evaluating the performance of different models to determine the best predictors of student success.

## **Project Overview**
This project uses a dataset from secondary school students to predict their final grades (`G3`) based on several factors such as their grades in the first (`G1`) and second (`G2`) terms, absences, and more.

The project:
- Explores the dataset to identify patterns and correlations.
- Applies and compares Linear Regression and K-Nearest Neighbors (KNN) models.
- Evaluates models using the Root Mean Squared Prediction Error (RMSPE).
- Discusses insights and implications for educational policy.

## **Key Findings**
1. **Exploratory Data Analysis:**
   - Age has little to no correlation with final grades.
   - Grades from Term I (`G1`) and Term II (`G2`) show a strong positive correlation with final grades (`G3`).
   - Absences negatively impact final grades but require cautious interpretation due to mixed results.

2. **Model Performance:**
   - KNN with predictors `G1`, `G2`, and Absences performed the best (lowest RMSPE).
   - Linear Regression is more interpretable and may be more suitable for policy discussions.

3. **Policy Implications:**
   - Support and incentives should focus on consistent academic performance throughout the year.
   - Age is not a significant predictor of final grades, which should influence targeted interventions.

## **Dataset**
- The dataset is from the research paper by Cortez & Silva (2008): [Using Data Mining to Predict Secondary School Student Performance](https://archive.ics.uci.edu/ml/datasets/Student+Performance).

## **Technologies Used**
- **Language:** R
- **Libraries:** `tidyverse`, `caret`, `e1071`, `ggplot2`

## **Future Questions**
- What additional factors contribute to good academic performance?
- How can schools minimize the negative impacts of absences on student grades?
- Can policy changes improve G1 and G2 scores to enhance final grades?
