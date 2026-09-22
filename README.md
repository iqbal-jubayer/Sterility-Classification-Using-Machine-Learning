<h1>Sterility Classification Using Machine Learning</h1>

> A comparative machine learning study for binary classification of sterile and 
non-sterile samples using multiple models and performance evaluation metrics.

## Overview
This project focuses on the binary classification of samples as sterile or non-sterile using machine learning techniques. 
The dataset was analyzed to understand its structure, identify relevant features, and determine an appropriate modeling approach.

Multiple machine learning models were implemented and evaluated alongside K-Means clustering. 
Their performance was compared using metrics including accuracy, precision, recall, F1-score, ROC curves, AUC, and confusion matrices.

The primary objective of the project was to investigate how different machine learning approaches perform on the given dataset 
and identify an appropriate model based on the experimental results. A detailed analysis of the dataset, preprocessing, feature 
selection, model implementation, evaluation, and findings is provided in the accompanying project report.

## Problem Statement

The objective of this project is to determine whether a given sample is sterile or non-sterile based on the available features 
in the dataset. This is formulated as a binary classification problem, where each sample belongs to one of two classes: 
sterile or non-sterile.

The project aims to analyze the dataset, identify relevant features, apply suitable machine learning techniques, and compare 
different models to determine how effectively they can distinguish between the two classes.

## Approach

The project follows the following workflow:

1. Dataset analysis
2. Exploratory data analysis
3. Feature analysis and selection
4. Data preprocessing
5. Machine learning model implementation
6. Model evaluation
7. Performance comparison
8. Final model selection

## Models Used

The following machine learning approaches were implemented and compared:

- Logistic Regression
- K-Nearest Neighbor
- Naive Bayes
- Neural Network
- K-Means

## Evaluation

The models were evaluated using multiple performance metrics, including:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC Curve
- AUC
- Confusion Matrix

The detailed experimental results and analysis are available in the
project report.

## Repository Contents

| File | Description |
|---|---|
| `Tree_Sterility_Dataset.csv` | Dataset used for the project |
| `Sterility_Classification_Analysis.ipynb` | Colab Notebook containing the implementation and analysis |
| `Sterility_Classification_Report.docx` | Detailed project report |


## Results

A summary of the model comparison is presented below.

| Model | Accuracy | F1 Score |
|---|---|---|
| Logistic Regression | 0.910233 | 0.761905 |
| K-Nearest Neighbor | 0.859964 | 0.315789 |
| Naive Bayes | 0.868941 | 0.386555 |
| Neural Network | 0.915619 | 0.666667 |

For the complete metrics, visualizations, and discussion, see the
[Project Report](Sterility_Classification_Report.docx).

## Conclusion

Conclusion

The experiments demonstrated that machine learning techniques can be effectively applied to the binary classification of sterile 
and non-sterile samples. Multiple models were trained and evaluated using accuracy, precision, recall, F1-score, ROC-AUC, 
and confusion matrices to provide a comprehensive comparison of their performance.

Based on the overall evaluation, Logistic Regression was selected as the most suitable model for this dataset, 
achieving a better recall and F1-Score. The results and detailed analysis are presented in the accompanying project report.

## Technologies

- Python
- Google Colab Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
