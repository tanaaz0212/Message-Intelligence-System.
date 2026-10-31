# Message-Intelligence-System.

# Spam Message Classification Using Probability and Machine Learning

## Project Overview

This project focuses on developing a machine learning classification system to identify whether a digital message is Spam or Legitimate.

Spam messages are unwanted messages that may contain advertisements, suspicious links, misleading information, or fraudulent content.

The project uses numerical features related to messages to train and evaluate different machine learning classification algorithms.

Three classification algorithms are implemented:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gaussian Naive Bayes

The performance of these models is compared using different evaluation metrics.

## Project Objectives

The main objectives of this project are:

- To understand and prepare a spam message classification dataset.
- To apply probability and machine learning concepts.
- To implement KNN, SVM, and Naive Bayes classifiers.
- To evaluate the models using classification metrics.
- To compare model performance and identify a suitable classifier.
- To understand the importance of feature scaling and probability in classification.

## Dataset Description

The project uses the Message Intelligence Dataset containing 5,200 records and 16 columns.

The target variable is:

`spam_label`

The target variable represents:

- `0` – Legitimate Message
- `1` – Spam Message

The dataset contains message-related features such as message length, special character counts, URL counts, keyword scores, sender activity, and time-based information.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Algorithms

### 1. K-Nearest Neighbors (KNN)

KNN is a distance-based classification algorithm.

It classifies a new observation by identifying its nearest neighbors and assigning the majority class.

Different values of K are tested to understand their effect on model performance.

### 2. Support Vector Machine (SVM)

SVM is a margin-based classification algorithm.

It identifies an optimal decision boundary that separates different classes.

The RBF kernel is used to handle non-linear relationships between features.

### 3. Gaussian Naive Bayes

Gaussian Naive Bayes is a probabilistic classification algorithm based on Bayes' Theorem.

It estimates the probability of a message belonging to a particular class using the observed features.

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Perform exploratory data analysis.
4. Check missing values and duplicate records.
5. Clean and prepare the dataset.
6. Separate input features and target variable.
7. Split the dataset into training and testing sets.
8. Apply feature scaling.
9. Implement KNN classifier.
10. Implement SVM classifier.
11. Implement Gaussian Naive Bayes classifier.
12. Evaluate all models.
13. Compare model performance.
14. Identify the best-performing classifier.
15. Present the final conclusion.

## Evaluation Metrics

The models are evaluated using the following metrics:

- **Accuracy:** Measures the overall percentage of correct predictions.
- **Precision:** Measures how many predicted spam messages are actually spam.
- **Recall:** Measures how many actual spam messages are correctly identified.
- **F1 Score:** Provides a balance between precision and recall.
- **Confusion Matrix:** Shows correct and incorrect classification results.

## How to Run the Project

### Requirements

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Steps

1. Download or clone this repository.
2. Open Jupyter Notebook.
3. Open `Spam_Message_Classification.ipynb`.
4. Make sure the dataset CSV file is in the correct folder.
5. Run all notebook cells from top to bottom.

## Project Conclusion

This project demonstrates the application of probability and machine learning techniques in spam message classification.

KNN, SVM, and Gaussian Naive Bayes are implemented and evaluated using multiple classification metrics.

The models provide different approaches to classification: distance-based, margin-based, and probabilistic.

The final model is selected based on the evaluation results, with particular attention to precision, recall, and F1 Score.

This project provides practical knowledge of supervised learning, probability, feature scaling, model evaluation, and classification.
