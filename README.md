# Heart-Disease-Prediction-using-Machine-Learning

### Introduction
Heart disease is one of the leading causes of death worldwide, making early detection and prevention crucial. Machine Learning offers powerful tools to predict heart disease, allowing for better research, prevention, and ultimately, healthier lives. This project focuses on the application of various machine learning algorithms to predict the presence of heart disease in patients using the UCI Heart Disease dataset.

### Project Overview
This project involves analyzing a heart disease patient dataset and applying several machine learning models to predict whether a patient is likely to have heart disease. The dataset was processed and explored through a series of steps including data cleaning, exploratory data analysis (EDA), and feature engineering.

### Machine Learning Algorithms Used
The following machine learning algorithms were employed to build predictive models:

1. **Logistic Regression (Scikit-learn)**
2. **Naive Bayes (Scikit-learn)**
3. **K-Nearest Neighbors (KNN) (Scikit-learn)**
4. **Decision Tree (Scikit-learn)**
5. **Random Forest (Scikit-learn)**

### Results
The models were evaluated based on accuracy. The highest accuracy achieved was **95%** using the **Random Forest** algorithm.

### Dataset
The dataset used for this project is the [UCI Heart Disease dataset](https://www.kaggle.com/ronitf/heart-disease-uci), which consists of 303 samples and 14 features, including age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

### How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, and `keras`).
3. Run the Jupyter Notebook (`HEART_ATTACK_ANALYSIS.ipynb`) to see the analysis and model training in action.
4. Modify parameters as needed and experiment with different algorithms to improve prediction accuracy.

### Conclusion
This project demonstrates how machine learning can be effectively used to predict heart disease. With an accuracy of 95%, the Random Forest algorithm proved to be the most effective model, though other models also provided valuable insights.

### Acknowledgements
This project was inspired by a Kaggle kernel titled "Binary Classification with Sklearn and Keras." Special thanks to the Kaggle community for the dataset and initial inspiration.