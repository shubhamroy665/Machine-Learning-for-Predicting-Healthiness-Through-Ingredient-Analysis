

<img src="./data/health.png" alt="Alt text" width="800" />


# Machine-Learning-for-Predicting-Healthiness-Through-Ingredient-Analysis

Introduction

SmartSnack is a machine learning project aimed at predicting the healthiness of food products based on ingredient analysis. By leveraging various classification algorithms, this project seeks to provide accurate tools to distinguish between healthy and unhealthy food options. With the growing emphasis on healthy eating habits, SmartSnack aims to empower consumers to make informed dietary choices and promote healthier eating habits.
Features

    Analysis of nutritional information for various food products, including traditional and fast food items.
    Utilization of multiple machine learning algorithms: Logistic Regression, K-Nearest Neighbors, Support Vector Machine, and Naive Bayes.
    Tailored healthiness classification for different demographic groups:
        Normal individuals
        Individuals with cholesterol issues
        Individuals with high fat intake
        Individuals with high sugar intake
    Data augmentation using SMOTE to address class imbalance.

Dataset

The dataset includes nutritional information for various food items, such as energy content, protein, carbohydrates, fat, fiber, sodium, iron, and cholesterol per 100 grams. The food items are labeled as "Healthy" or "Unhealthy" based on expert judgment. Data sources include the USA health ministry and Kaggle. You can access the dataset here.
Methodology

SmartSnack employs the following machine learning algorithms:

    Logistic Regression: Models the probability of a binary outcome using a logistic function.
    K-Nearest Neighbors (KNN): Classifies data points based on the majority class among their k nearest neighbors.
    Support Vector Machine (SVM): Constructs hyperplanes in a high-dimensional space to separate data points into different classes.
    Naive Bayes: Models the probability of a data point belonging to a particular class based on the conditional probabilities of its features.

Experimental Results
Performance Metrics

The performance of each algorithm is evaluated using accuracy, precision, recall, and F1-score. Cross-validation is conducted to assess the robustness of the models.
Normal Individuals

    Logistic Regression: 97.61%
    K-Nearest Neighbors: 97.61%
    Support Vector Machine: 91.42%
    Naive Bayes: 99.00%

Individuals with Cholesterol Issues

    Logistic Regression: 95.82%
    K-Nearest Neighbors: 96.90%
    Support Vector Machine: 91.76%
    Naive Bayes: 94.14%

Individuals with High Fat Intake

    Logistic Regression: 97.61%
    K-Nearest Neighbors: 97.61%
    Support Vector Machine: 91.42%
    Naive Bayes: 99.96%

Individuals with High Sugar Intake

    Logistic Regression: 89.26%
    K-Nearest Neighbors: 98.86%
    Support Vector Machine: 95.57%
    Naive Bayes: 91.58%

Summary

SmartSnack demonstrates the application of machine learning techniques to predict the healthiness of food products based on ingredient analysis. The project provides valuable insights into the effectiveness of different machine learning models in classifying food items for diverse populations, contributing to the development of tools that can aid consumers in making informed dietary choices and promoting healthier eating habits.
Contributors

    Shubham Roy (B2330040), roy.sonai665@gmail.com
    Parimal Bera (B2330031), parimalbera244@gmail.com

References

    BDA. Big data analytics. Link
    Bernhard E Boser, Isabelle M Guyon, and Vladimir Naumovich Vapnik. A training algorithm for optimal margin classifiers. In Proceedings of the Fifth Annual Workshop on Computational Learning Theory, pages 144–152. ACM, 1992.
    Leo Breiman. Random forests. Machine Learning, 45(1):5 – 32, 2001.
    Soumita Kundu. Nutritionist at RSV Hospital, Tollygunge, Kolkata, 2024.
    Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar. Foundations of Machine Learning. The MIT Press, 2nd edition, 2018.
    Frank Rosenblatt. Principles of neurodynamics: Perceptrons and the theory of brain mechanisms. Technical report, Cornell Aeronautical Laboratory, 1961.
    Shubham Roy and Parimal Bera. My data of food. Link, 2024.
