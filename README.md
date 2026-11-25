# CIE2 Activity 2 – Binary Classification using Logistic Regression

## Project Description
This project demonstrates binary classification using the Logistic Regression algorithm and the Breast Cancer Wisconsin dataset.

## Objective
To build a classification model that predicts whether a tumour is malignant or benign.

## Dataset
- Dataset: Breast Cancer Wisconsin Dataset
- Source: Scikit-learn
- Type: Binary Classification

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Steps Performed
1. Imported required libraries.
2. Loaded and explored the dataset.
3. Checked class distribution.
4. Prepared features and target variables.
5. Split the data into training and testing sets using stratification.
6. Explained and visualized the sigmoid function.
7. Built and trained the Logistic Regression model.
8. Predicted probabilities and class labels.
9. Created a confusion matrix.
10. Evaluated accuracy, precision, recall, specificity, F1-score and ROC-AUC.
11. Compared the model with a majority-class baseline.
12. Evaluated different classification thresholds (0.3, 0.5 and 0.7).
13. Plotted the ROC curve.
14. Tested a new prediction.

## Algorithm
Logistic Regression

## Results
The model classifies tumours as malignant or benign. Refer to the notebook for implementation, evaluation metrics and visualizations.

## Repository Owner
GitHub: https://github.com/monu123-ingale

## Submission
GitHub ID: https://github.com/complexiota

 ## Decision Log

1. Used stratified train-test splitting to maintain class distribution.
2. Considered false negatives important because missing malignant cases can be risky.
3. Compared decision thresholds of 0.3, 0.5 and 0.7.
4. Recommended a threshold of 0.3 based on the model's recall and F1-score.
