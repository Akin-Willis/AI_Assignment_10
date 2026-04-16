# Assignment 10: Customer Review Sentiment Analysis

## Project Description
This project performs sentiment analysis on Amazon Alexa
customer reviews using Natural Language Processing and
a Random Forest Classifier. The goal is to classify
customer reviews as positive or negative based on the
review text and product variation.

## Dataset
- Name: Amazon Alexa Reviews
- Source: Kaggle
- File: amazon_alexa.tsv
- Target column: feedback (1 = positive, 0 = negative)
- Features used:
  - verified_reviews
  - variation

## Requirements
The following libraries are required to run this notebook:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow

## How to Set Up and Run the Notebook

Step 1
Open Google Colab at https://colab.research.google.com

Step 2
Upload the notebook file to Colab or open it from GitHub.

Step 3
Upload the dataset file amazon_alexa.tsv to your
Google Drive.

Step 4
Mount your Google Drive in the first cell and update
the file path to match where you saved the dataset.

Step 5
Run each cell from top to bottom in order.

Step 6
Make sure all outputs are visible before saving as PDF.

## Notebook Structure
1. Import Libraries and Dataset
2. Preview Reviews and Feedback
3. Data Visualization and Clean Up
4. Drop Irrelevant Columns
5. One-Hot Encoding
6. Tokenization using CountVectorizer
7. Prepare Data for Modeling
8. Train and Test Split
9. Build and Train the Model
10. Evaluate Model
11. Classification Report
12. Training History Plots
13. Random Forest Classifier
14. Feature Importance
15. Predict Sentiment on New Reviews
