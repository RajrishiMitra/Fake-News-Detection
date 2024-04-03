# Fake News Detection using Machine Learning

This project aims to detect fake news using machine learning techniques. The dataset used in this project consists of textual data from news articles along with their labels indicating whether the news is real or fake. The detection is performed by training a logistic regression model on the provided dataset.

## Project Overview

The project consists of the following steps:

1. **Data Preprocessing**: 
   - Importing necessary modules.
   - Reading the dataset.
   - Handling missing values.
   - Merging relevant attributes (author and title) to form content.
   - Stemming: reducing words to their root forms.

2. **Text Vectorization**: 
   - Converting textual data into numerical form using TF-IDF vectorization.

3. **Model Training**:
   - Splitting the data into training and testing sets.
   - Training a logistic regression model.

4. **Model Evaluation**:
   - Evaluating the model's performance on training and testing data.

## Code Explanation

The provided code performs the following tasks:

- Imports necessary modules such as pandas, re, NLTK, and scikit-learn.
- Reads the dataset and handles missing values.
- Merges 'author' and 'title' attributes to form 'content'.
- Applies stemming to the content data.
- Converts textual data into numerical form using TF-IDF vectorization.
- Splits the data into training and testing sets.
- Trains a logistic regression model on the training data.
- Evaluates the model's accuracy on both training and testing data.
- Performs prediction on a sample data point and classifies it as real or fake news.

## How to Use

1. Clone the repository or download the project files.
2. Ensure you have the necessary dependencies installed (Pandas, NLTK, Scikit-learn).
3. Run the provided Python script or Jupyter Notebook to train the model and make predictions.

## Dataset

The dataset used in this project contains textual data from news articles along with their labels indicating whether the news is real or fake.

## Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- Jupyter Notebook

## Conclusion

This project demonstrates the application of machine learning techniques in detecting fake news. By training a logistic regression model on a labeled dataset, we can classify news articles as real or fake with a certain level of accuracy.

