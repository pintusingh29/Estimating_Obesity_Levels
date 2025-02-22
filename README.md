# Estimating_Obesity_Levels
Estimating Obesity Levels Based on Eating Habits and Physical Condition

This project deals with the dataset of "Estimation of Obesity Levels Based on Eating Habits and Physical Condition", found in the UCI Machine Learning repository. The dataset very well maps lifestyle, dieting habits, and demographic attributes and can be used to predict obesity levels. The classification problem will use two methods, under supervised learning, in R: Random Forest and Artificial Neural Networks (ANNs). This will showcase their relative merits and demerits. Approval will be or has been sought from the module leader with respect to this dataset. 

2. Dataset Description

The dataset, gathered over the course of the past six or seven years, contains 2102 instances with 17 attributes, among which are:

•	Age, Gender, BMI, Physical Activity Level, Consumption of High Caloric Food

•	Target variable NObesity is the variable that classifies individuals from seven levels of obesity (ranging from Insufficient Weight to Obese Type III).

•	It is a mixture of numeric and categorical, therefore, appropriate preprocessing procedures are warranted.

4. Research Questions

•	What is the accuracy of predicting obesity levels with lifestyle and dietary factors?

•	Which one of the two methods chosen (Random Forest and ANN) works better for this classification task and why?

•	Which lifestyle and dietary factors are the most significant in differentiating levels of obesity?

6. Methodology

The analysis will be done using R as follows:

4.1 Data Preprocessing

•	Dealing with Missing Values: If there are missing values, the suitable imputation methods would be applied (e.g., mean/median for numerical features, mode for categorical features or KNN imputation).

•	Data Cleaning: All duplicates will be deleted, inconsistencies or outliers investigated and dealt with.

•	Encoding Categorical Variables: Apply either one-hot encoding or label encoding where applicable.

•	Feature Scaling: Numerical features would need to be standardized (z-score normalization, min-max scaling).

4.2 Exploratory Data Analysis (EDA)

•	Descriptive Statistics: Summary statistics for numerical features and frequency distributions for categorical features.

•	Visualizations:

o	Histograms and box plots for numerical attributes

o	Bar charts for categorical features

o	Correlation heat maps for numerical features

o	Feature importance plots (after model training)

•	Analysis of Class Imbalance: Techniques like oversampling or undersampling will be adopted if necessary.

4.3 Model Building and Evaluation

Random Forest

  •	Applied via randomForest.

  •	Hyperparameter tuning (like number of trees, depth of trees) will be performed via cross-validation.

Artificial Neural Network (ANN)

  •	Implemented using keras or tensorflow.
  
  •	Architecture (number of layers, neurons per layer, activation function) will be carefully selected and tuned.

Evaluation Metrics

  •	Accuracy

  •	Precision, recall, and F1-score (for each class and weighted average)
  
  •	Confusion matrix
  
  •	ROC curves and AUC (Area Under Curve)
  
  •	Cross-validation (k-fold cross-validation for robustness, k-value should be specified)

8. Model Comparison and Selection

  •	The Random Forest and ANN models will be compared based on performance and evaluation metrics. 

  •	The best-performing model (based on justification provided from chosen metrics) will be selected as final. 

  •	The reasons for performance differences will be discussed in detail. 

9. Feature Importance Analysis
   
  •	Random Forest: built-in feature importance measures. 

  •	For ANN: sensitivity/weight analysis.

11. Report and Expected Outcomes

The final report will include:
  
  •	Introduction to the problem and dataset

  •	Methodology (data preprocessing, model building, and evaluation techniques)
  
  •	Comprehensive presentation of results (tables, figures, and interpretations)
  
  •	Strengths and weaknesses of each model
  
  •	Feature importance analysis
  
  •	A conclusion of findings and implications
  
  •	A properly formatted reference list

13. Software and Tools

  •	R
  
  •	R packages: caret, randomForest, keras, tensorflow, ggplot2, dplyr
