# Student Performance Predictor
This project aims to analyze and predict student performance in an entrance examination using exploratory data analysis (EDA) and machine learning techniques.

## Objectives
* Understand the factors that influence student performance.
* Build predictive models to classify student outcomes.
* Compare different machine learning algorithms in terms of accuracy and performance.

## Dataset
The dataset used is Student_Performance_on_an_Entrance_Examination.csv, which includes information about:
* Gender
* {arents' education level
* Residence location
* Type of school
* Access to resources such as internet and private tutoring
* Exam performance (target variable)

 ##Exploratory Data Analysis
The EDA included:
* Distribution analysis of categorical variables
* Correlations with the target variable (performance)
* Bar plots and heatmaps to highlight patterns

## Machine Learning Models
The following algorithms were applied and compared:
* Decision Tree
* K-Nearest Neighbors (KNN)
* Random Forest
* Support Vector Machine (SVM)

## Techniques Used
* Preprocessing with LabelEncoder
* Train-test split (80/20)
* Evaluation using accuracy, classification report, and confusion matrix
* Hyperparameter tuning with GridSearchCV

## Results
* The best-performing model was the Support Vector Classifier (SVC) with a linear kernel.
* The model showed strong performance for class 0 (precision: 0.84, recall: 0.93, F1-score: 0.88).
* However, performance on class 1 was very poor (precision: 0.25, recall: 0.09, F1-score: 0.13).
* Classes 2 and 3 showed moderate results, but still need improvement.
* Overall accuracy: 51%, indicating that the model is underperforming, especially due to class imbalance.

## Libraries Used
* pandas, numpy
* seaborn, matplotlib
* scikit-learn

## Check it out!
If you're interested in educational data, model performance evaluation, or classification with imbalanced datasets, check out this project and leave your feedback!
