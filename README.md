# **Fake News Classification using Explainable AI**

This repository presents a comprehensive study on Fake News Classification using two datasets: the ISOT benchmark dataset and the Fake News dataset from Kaggle. We employ machine learning models and Explainable AI (XAI) techniques to gain insights into model predictions, ensuring transparency and interpretability.

# *Project Overview:*

This project aims to classify news articles as Fake or Real using various machine learning models. We explore two widely used fake news datasets and demonstrate the importance of model interpretability by leveraging Explainable AI techniques, specifically SHAP (SHapley Additive exPlanations), to understand model decisions.

# *Datasets:*

ISOT Dataset

Description: Contains news articles from legitimate and fake news sources, commonly used as a benchmark for fake news detection tasks.

Size: 44,898 articles

Classes: Real and Fake news

Source: ISOT Fake News Dataset

Kaggle Fake News Dataset

Description: Includes features like news title, text, and author, making it suitable for building models that classify news credibility.

Size: ~20,800 articles

Classes: Real and Fake news

Source: Kaggle Fake News Dataset

# *Modeling Approach*

We employ several machine learning models to tackle the classification task:

Logistic Regression

Random Forest

Support Vector Machines (SVM)

Naive Bayes

# *Feature Engineering*

For both datasets, we apply the following preprocessing techniques:

Text Cleaning: Removing punctuation, stopwords, and special characters

Vectorization: Using TF-IDF for feature extraction

Handling Missing Values: Addressing missing data for robustness

# *Explainable AI (XAI) Techniques*

Model transparency is essential for understanding predictions, especially in critical applications like fake news detection. We employ SHAP (SHapley Additive exPlanations) to explain the contribution of each feature to the model’s predictions.

SHAP: A cooperative game theory-based method that quantifies the impact of each feature on the final prediction, helping to validate model decisions and detect potential biases.

# *Results*

Model Performance: We compare models based on accuracy, precision, recall, and F1-score.

Explanations: SHAP visualizations provide insights into how features influence classification decisions.

# *Future Work*

Deep Learning Models: Incorporate LSTM or Transformer-based architectures to improve accuracy on larger datasets.

Real-time Detection: Develop a web service or API for real-time fake news detection.

Additional Datasets: Explore diverse datasets to enhance model generalizability and robustness.
