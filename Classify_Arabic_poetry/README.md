# Arabic Poetry Classification

This project focuses on the classification of Arabic poetry using machine learning techniques. The dataset used contains various categories of Arabic poems, and the model aims to categorize them accurately.

## Dataset

The dataset is sourced from [Kaggle's Arabic Poetry Dataset](https://www.kaggle.com/datasets/fahd09/arabic-poetry-dataset-478-2017), which includes poems from various poets and different styles.

## Project Structure

- **Data Preprocessing**: The dataset is cleaned and preprocessed, including handling missing values, removing duplicates.
- **Feature Extraction**: Text features are extracted using TF-IDF vectorization.
- **Model Training**: Several machine learning models are used, including RandomForestClassifier and DecisionTreeClassifier, with techniques like oversampling to handle class imbalance.
- **Evaluation**: The models are evaluated based on accuracy and classification reports, providing detailed metrics for each class.

## Installation

To run this project, you'll need to install the necessary libraries. Use the following commands:

```bash
pip install -q pyarabic imbalanced-learn
pip install nltk scikit-learn matplotlib wordcloud
