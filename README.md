# Vehicle CO2 Emissions Prediction

## Overview

This repository contains a project focused on predicting vehicle CO2 emissions based on various vehicle specifications. The dataset, sourced from Kaggle, includes information on different vehicle categories and their attributes such as the number of cylinders, type of car, fuel consumption metrics, and more.

## Dataset

The dataset includes:
- **Number of Cylinders**
- **Type of Car**
- **Fuel Consumption Metrics**
- **CO2 Emissions**

This data is crucial for analyzing the impact of vehicle specifications on CO2 emissions, which are significant contributors to global warming and climate change.


## Analysis and Modeling

### Exploratory Data Analysis (EDA)

Performed EDA to understand the distribution and relationships within the dataset. This included:
- Data cleaning and preprocessing
- Visualization of feature distributions
- Correlation analysis to identify impactful features

### Feature Selection

Based on correlation analysis, the most impactful features were selected for modeling.

### Models Implemented

1. **Linear Regression**: Tested to find the most effective predictor for CO2 emissions. The model achieved an accuracy of 87% after scaling the data.

2. **Support Vector Machine (SVM)**: Implemented for classification and regression tasks.

3. **K-Nearest Neighbors (KNN)**: Used for classification and regression analysis.

4. **Decision Tree**: Applied to assess feature importance and make predictions.

### Model Performance

- **Linear Regression**: Achieved 87% accuracy.
- **SVM, KNN, and Decision Tree**: Evaluated to compare performance with Linear Regression.

[Model Performance](![image](https://github.com/user-attachments/assets/09e0c51a-37c4-4eee-8eb9-9d7166874d52)
)

## Getting Started

### Prerequisites

- **Python 3.x**
- **Required Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your_username/your_repo.git
   cd your_repo
