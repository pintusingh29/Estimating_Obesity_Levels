📊 Estimation of Obesity Levels Based on Eating Habits and Physical Condition 🍽️
🏆 Overview
This project explores the dataset "Estimation of Obesity Levels Based on Eating Habits and Physical Condition" from the UCI Machine Learning Repository. The dataset maps lifestyle, dietary habits, and demographic attributes to predict obesity levels. This classification problem is approached using 🌲 Random Forest and 🧠 Artificial Neural Networks (ANNs) in R, providing insights into their relative performance and effectiveness.

📑 Dataset Description
The dataset, collected over six to seven years, consists of 2102 instances with 17 attributes, including:

📌 Predictor Variables: Age, Gender, BMI, Physical Activity Level, Consumption of High-Caloric Food, etc.

🎯 Target Variable: NObesity (categorizing individuals into seven levels of obesity, from Insufficient Weight to Obese Type III).

📊 Data Types: A mixture of numerical and categorical features requiring appropriate preprocessing.

🔍 Research Questions
How accurately can obesity levels be predicted using lifestyle and dietary factors? 🤔

Which classification method (🌲 Random Forest vs. 🧠 ANN) performs better for this task, and why? 🏆

What are the most significant lifestyle and dietary factors influencing obesity classification? 🍔🥗

🛠️ Methodology
1️⃣ Data Preprocessing
🛑 Handling Missing Values: Imputation using mean/median (numerical features) and mode/KNN (categorical features).

🧹 Data Cleaning: Removing duplicates, detecting and handling outliers.

🔠 Encoding Categorical Variables: One-hot encoding or label encoding as needed.

⚖️ Feature Scaling: Standardization (Z-score) or Min-Max scaling.

2️⃣ Exploratory Data Analysis (EDA)
📊 Descriptive Statistics: Summary statistics and frequency distributions.

📈 Visualizations:

📉 Histograms & box plots (numerical attributes)

📊 Bar charts (categorical attributes)

🔥 Correlation heat maps

⭐ Feature importance plots

⚠️ Class Imbalance Analysis: Using oversampling/undersampling if necessary.

3️⃣ Model Building and Evaluation
🌲 Random Forest
Implemented via randomForest package.

🎯 Hyperparameter tuning using cross-validation (number of trees, depth, etc.).

🧠 Artificial Neural Network (ANN)
Implemented using keras and tensorflow.

Optimized architecture: 🔢 number of layers, neurons, activation functions.

📏 Evaluation Metrics
✅ Accuracy

📌 Precision, Recall, F1-score (for each class & weighted average)

📊 Confusion Matrix

📈 ROC Curve & AUC (Area Under Curve)

🔄 Cross-validation (k-fold for robustness)

4️⃣ Model Comparison & Selection
📊 Performance of 🌲 Random Forest and 🧠 ANN will be compared.

🏆 The best-performing model will be selected based on key metrics.

🔍 Justifications for performance differences will be discussed in detail.

5️⃣ Feature Importance Analysis
🌲 Random Forest: Built-in feature importance measures.

🧠 ANN: Sensitivity analysis (e.g., weight analysis).

🎯 Expected Outcomes
The final report will include:

📝 Problem definition and dataset details.

🔬 Methodology (preprocessing, modeling, evaluation techniques).

📊 Performance comparison of Random Forest and ANN.

📌 Feature importance insights.

🎯 Conclusion on model performance and findings.

🛠️ Tools & Technologies
💻 Programming Language: R

📚 Libraries Used:

caret, randomForest, keras, tensorflow

ggplot2, dplyr (for visualization & data manipulation)

🙌 Acknowledgment
The dataset is sourced from the 📂 UCI Machine Learning Repository, and the project is part of coursework for the 🎓 MSc in Data Science program at the 🏫 University of East London.

🔗 Connect & Contribute 🚀
Feel free to explore, fork, and contribute to the project. Feedback and suggestions are welcome! 💡✨
