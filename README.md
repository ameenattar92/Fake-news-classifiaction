Fake News Classification using Explainable AI

This repository contains a comprehensive study on Fake News Classification using two datasets: the ISOT benchmark dataset and the Fake News dataset from Kaggle. 
We employ machine learning models and Explainable AI (XAI) techniques to provide insights into model predictions.


Project Overview:

This project aims to classify news articles as Fake or Real using machine learning models. We explore two widely used fake news datasets and demonstrate the importance of model interpretability by applying Explainable AI techniques, such as SHAP (SHapley Additive exPlanations), to understand model decisions.

Datasets

ISOT Dataset

The ISOT dataset contains news articles from legitimate and fake news sources. It is commonly used as a benchmark for fake news detection tasks.

Size: 44,898 articles
Classes: Real and Fake news
Source: ISOT Fake News Dataset
Kaggle Fake News Dataset
The Fake News dataset from Kaggle includes various features like the news title, text, and author. It is suitable for building models that classify the credibility of news articles.

Size: ~20,800 articles
Classes: Real and Fake news
Source: Kaggle Fake News Dataset
Modeling Approach
We employ several machine learning models to tackle the classification task:

Logistic Regression
Random Forest
Support Vector Machines (SVM)
XGBoost
Feature Engineering
For both datasets, we apply preprocessing techniques like:

Text cleaning (removing punctuation, stopwords, etc.)
Vectorization (using TF-IDF and Word2Vec)
Handling missing values and balancing the dataset
Explainable AI (XAI) Techniques
Model transparency is key for understanding predictions, especially in critical applications like fake news detection. We apply the following XAI methods to explain the results:

SHAP (SHapley Additive exPlanations):

A method based on cooperative game theory that explains the contribution of each feature to the model’s prediction.

LIME (Local Interpretable Model-Agnostic Explanations): 
A technique to locally approximate the decision boundary of black-box models.
These explanations help in validating model predictions and detecting potential biases in the model.

(We have used only SHAP in our experiments)

Results:

Accuracy: We compare model performance on both datasets using accuracy, precision, recall, and F1-score.

Explanations: SHAP and LIME visualizations provide insights into how each feature contributes to the classification decision.

Future Work:

Deep Learning Models: Incorporate LSTM or Transformer models to improve accuracy on larger datasets.

Real-time Detection: Implement the model as a web service or API for real-time fake news detection.

Additional Datasets: Explore more datasets to enhance model generalizability.

