## Spam Detection using Naive Bayes:
## Project Overview:

This project is a Machine Learning-based Spam Detection System that classifies messages as Spam or Not Spam (Ham) using the Naive Bayes algorithm.

The model is trained on a dataset of messages and learns patterns from the text to predict whether a new message is spam or not spam.

## Objective:

The main objective of this project is to build a simple and effective text classification model that can automatically identify unwanted or spam messages.

## Machine Learning Algorithm: Naive Bayes

Naive Bayes is a probabilistic machine learning algorithm that is commonly used for text classification problems such as:

Spam detection

Sentiment analysis

Document classification

Text categorization

It works by calculating the probability of a message belonging to a particular class based on the words present in the message.

## Project Workflow:
Dataset
   ↓
Data Loading
   ↓
Data Cleaning & Preprocessing
   ↓
Text Feature Extraction
   ↓
Train-Test Split
   ↓
Naive Bayes Model
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
## Technologies & Libraries:
Python

Pandas – Data loading and manipulation

NumPy – Numerical operations

Scikit-learn – Machine Learning and model evaluation

Matplotlib / Seaborn – Data visualization (if used)

Jupyter Notebook – Development and experimentation

## Dataset:

The project uses a dataset containing text messages labeled as:

Spam – Unwanted or promotional messages

Ham – Legitimate/non-spam messages

The dataset is loaded using Pandas.

Note: The dataset uses latin-1 encoding while reading the CSV file because the file contains characters that may not be properly decoded using UTF-8.

# Model Training:

The text data is converted into numerical features so that it can be processed by the machine learning algorithm.

The processed features are then provided to the Naive Bayes classifier, which learns the relationship between message content and its corresponding class.

## Model Evaluation:

The trained model is evaluated using standard classification metrics such as:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

These metrics help measure how effectively the model distinguishes between spam and ham messages.

## Prediction:

After training, the model can be used to classify new messages.

For example:

Input:
"Congratulations! You have won a free prize."

Prediction:
Spam
Input:
"Hey, are we meeting today?"

Prediction:
Ham
## Key Learning Outcomes:

Through this project, I learned about:

Text preprocessing for Machine Learning
Feature extraction from text data
Naive Bayes classification
Train-test splitting
Model evaluation
Classification metrics
Confusion matrix
Handling CSV encoding
Building a basic Machine Learning classification project.

Future Improvements:

The project can be further improved by:

Testing different text vectorization techniques

Comparing multiple Machine Learning algorithms

Hyperparameter tuning

Handling class imbalance

Deploying the model as a web application or API.

Author:

Nidhi Sharma

This project was created as part of my Machine Learning learning journey to understand practical text classification and spam detection using Python and Naive Bayes.
