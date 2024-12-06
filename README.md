# Heart Disease Prediction

This Machine Learning project focuses on predicting heart disease based on health information using various machine learning models. The goal is to analyze the dataset, apply dimensional reduction techniques, and evaluate different machine learning models to determine the most effective approach for this prediction task.

## Project Overview

### Objective
1. **Data Analysis**:
   - Explore the dataset attributes, their meanings, and encoding.
   - Assess the linearity of the data and the impact of attributes on prediction accuracy.

2. **Dimensional Reduction**:
   - Use feature selection and Principal Component Analysis (PCA) to reduce data dimensions.
   - Apply Support Vector Machines (SVM) on various subsets of data to evaluate performance.

3. **Model Evaluation**:
   - Compare performance of multiple models: SVM (linear, RBF, polynomial, sigmoid kernels), Logistic Regression, Perceptron, and Linear Discriminant Analysis.
   - Analyze the strengths and limitations of these models based on dataset properties.

### Dataset
The dataset contains 13 attributes representing patient health information and a binary target:
- **Target**: Indicates presence (1) or absence (0) of heart disease.

Attributes include patient demographics, medical test results, and lifestyle-related factors, such as:
- Age, Gender, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol (chol), etc.

### Approach
1. **Data Analysis**:
   - Visualize and examine attribute distributions, correlations, and potential decision boundaries.
   - Determine the attributes most strongly correlated with heart disease.

2. **Dimensional Reduction**:
   - Use PCA to reduce data dimensions and evaluate its effect on model performance.
   - Select feature subsets based on correlation analysis and test them with linear and non-linear SVM models.

3. **Model Testing**:
   - Implement SVM with different kernels, Logistic Regression, Perceptron, and Linear Discriminant Analysis.
   - Evaluate model accuracy and discuss overfitting and bias for non-linear kernels.

## Implementation
1. **Data Analysis**:
   - Correlation matrix analysis to identify impactful features.
   - Attribute visualization to explore linearity.

2. **Dimensional Reduction**:
   - PCA applied to project the data into 2D for linearity testing.
   - Feature selection based on correlation to target.

3. **Model Implementation**:
   - Use Python and popular ML libraries to test the following:
     - SVM with linear, RBF, polynomial, and sigmoid kernels.
     - Logistic Regression, Perceptron, and Linear Discriminant Analysis.

4. **Performance Comparison**:
   - Models are compared based on accuracy, robustness, and appropriateness for the dataset.

## Key Insights
- Linear models (SVM, Logistic Regression, Linear Discriminant Analysis) performed best due to the dataset's partial linearity.
- PCA and feature selection effectively reduced noise and maintained model performance.
- The project highlights the importance of data encoding, analysis, and testing multiple models to identify the optimal approach.

---

For additional details, refer to the [report](ML_report.pdf).
