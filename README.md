Heart Disease Prediction – Task 5  
Train-Test Split & Evaluation Metrics

==================================================

PROJECT OVERVIEW
--------------------------------------------------
This project demonstrates how to:
- Load a Heart Disease dataset
- Split data into training and testing sets
- Train a Logistic Regression model
- Evaluate model performance using Accuracy, Precision, Recall
- Understand the Confusion Matrix

This task helps interns understand MODEL EVALUATION FUNDAMENTALS.

--------------------------------------------------

FILES IN THIS PROJECT
--------------------------------------------------
heart.csv        -> Heart Disease dataset  
task5.py  -> Python script for training & evaluation  
README.md        -> Project documentation  

--------------------------------------------------

DATASET DESCRIPTION (heart.csv)
--------------------------------------------------

Column Name   | Meaning
----------------------------------------------
age           | Age of patient  
sex           | 1 = male, 0 = female  
cp            | Chest pain type (0–3)  
trestbps      | Resting blood pressure  
chol          | Serum cholesterol (mg/dl)  
fbs           | Fasting blood sugar > 120 mg/dl  
restecg       | Resting ECG results  
thalach       | Max heart rate achieved  
exang         | Exercise induced angina  
oldpeak       | ST depression  
slope         | Slope of ST segment  
ca            | Number of major vessels (0–4)  
thal          | Thalassemia (0–3)  
target        | 1 = disease, 0 = no disease  

--------------------------------------------------

REQUIREMENTS
--------------------------------------------------
Install required libraries using:

pip install pandas scikit-learn

--------------------------------------------------

WHAT THE CODE DOES
--------------------------------------------------
1. Loads the dataset  
2. Splits data into training (80%) and testing (20%)  
3. Trains a Logistic Regression model  
4. Predicts results on test data  
5. Calculates:
   - Accuracy
   - Precision
   - Recall  
6. Prints confusion matrix and classification report  

--------------------------------------------------

EVALUATION METRICS EXPLAINED
--------------------------------------------------

Accuracy:
Overall correctness of predictions.

Precision:
How many predicted disease cases were actually correct.

Recall:
How many actual disease cases were correctly detected.

--------------------------------------------------

CONFUSION MATRIX FORMAT
--------------------------------------------------

[[TN  FP]
 [FN  TP]]

TN -> True Negative (correct healthy)  
FP -> False Positive (wrong disease)  
FN -> False Negative (missed disease)  
TP -> True Positive (correct disease)  

--------------------------------------------------

EXPECTED OUTCOME
--------------------------------------------------
After completing this task, the intern will understand:

- Why train-test split is required  
- How to train a basic ML model  
- How to evaluate a classification model  
- How to interpret confusion matrix & metrics  

--------------------------------------------------

