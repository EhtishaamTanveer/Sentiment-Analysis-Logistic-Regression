# Sentiment Analysis: Logistic Regression

## Project Overview

This project performs basic Sentiment Analysis on text data (tweets) using the Logistic Regression model. The goal is to classify textual data into positive and negative sentiment categories. This type of analysis is widely used in areas such as product reviews, social media sentiment tracking, and customer feedback analysis.

## Key Highlights:

* **Data Preprocessing:** Handling of tweets through tokenization, stopword removal, and vectorization
* **Modeling:** Using Logistic Regression to predict sentiment.
* **Evaluation:** Model performance is evaluated using *accuracy* metric

## Project Setup
### Dataset

The dataset used in this project contains textual data (e.g., product reviews, tweets, or movie reviews) that are labeled as positive or negative. You can use any publicly available dataset for sentiment analysis (e.g., the IMDB reviews dataset or Twitter sentiment dataset).

### Steps in the Project

* Data Preprocessing:
    - Train-Test Splitting: Dividing the dataset into training and testing parts
    - Text Cleaning: Removing special characters, numbers, and stopwords.
    - Tokenization: Breaking text into individual words.

* Model Training:
    - Logistic Regression is trained on the processed text data to predict sentiment labels.

* Model Evaluation:
    - The model's performance is evaluated on a held-out test set using the accuracy metric.

### Files in the Repository
   - sentiment-analysis-lr.ipynb: The jupyter notebook containing the project code
   - utils.py: Contains the helper functions that utilized in the main notebook
   -  README.md: This file.

## Model Performance
Once the model is trained and evaluated, the results will be displayed, showing how well the model performs on the test set. Error Analysis is also performed to observe which tweets from the test set were incorrectly classified. Additionally, users will be allowed to type in their own tweets and let the trained model classify it.

### Sample Output
- Logistic regression model's accuracy = 99.50 %

The accuracy metric helps you understand how well the model is classifying the sentiment of the text.

### Example
**Input Text:** "This is a ridiculously bright movie. The plot was terrible and I was sad until the ending!"

**Predicted Sentiment:** Negative 

## Acknowledgements

* Dataset sources:
  * [Twitter](https://www.x.com)   
  * [Coursera](https://www.coursera.org/)
    
* Libraries used:
  * NumPy for vectorized calculations.
  * Pandas for data handling.
  * NTLK for accessing tweets dataset.
