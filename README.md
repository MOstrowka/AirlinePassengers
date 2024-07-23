# Airline Passenger Satisfaction Analysis

![image](https://dynamic-media-cdn.tripadvisor.com/media/photo-o/0e/cd/51/f6/lot-polish-airlines.jpg?w=1200&h=-1&s=1)

## Overview

This repository contains my project for analyzing and predicting airline passenger satisfaction. I used a dataset from an airline passenger satisfaction survey, which includes various features related to passengers' travel experiences.

### Dataset

The dataset includes the following selected features:
- Online boarding
- Class
- Type of Travel
- Inflight entertainment
- Seat comfort
- On-board service
- Leg room service
- Cleanliness
- Flight Distance
- Inflight wifi service
- Customer Type

### Exploratory Data Analysis (EDA)

During EDA, I:
- Checked for missing values and handled them appropriately.
- Performed label encoding for categorical features.
- Visualized the distribution of various features.
- Created correlation matrices to understand relationships between features.
- Visualized the impact of different features on passenger satisfaction using histograms and boxplots.

### Models Used

I trained and evaluated several models to predict passenger satisfaction:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **XGBoost Classifier**
4. **Neural Network (using Tensorflow)**

### Model Performance

The models were evaluated using metrics such as Accuracy, Precision, Recall, F1 Score, and ROC AUC Score. Here are the accuracy scores for each model:

- **Logistic Regression**: 0.8610
- **Random Forest Classifier**: 0.9392
- **XGBoost Classifier**: 0.9494
- **Neural Network (Tensorflow)**: 0.9504

The Neural Network model achieved the highest accuracy, but also is leading in the rest of metrics.

### Results

The results of the model performance and confusion matrices are saved in the `Results` folder, where you can find detailed metrics and visualizations.

## Conclusion

This project demonstrates the process of analyzing and predicting airline passenger satisfaction using various machine learning models. The Neural Network model provided the best overall performance in this case.

Feel free to explore the repository and use the code as a reference for similar projects.
