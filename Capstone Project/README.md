# Capstone Project
## **Title:** Amazon Reviews Sentiment Analysis

## Problem Description

The problem here that Amazon have a huge number of reiews on products sold on their website and they want to know how the customers feel about these products. Are they satisfied or not.

**So:** here they want to use this data that they have to study this case and based on the results they can improve their sales or can detect if this product satisfying the customers or not.

To solve this problem I want to use this data set to build a classifier that can classify the review to Positive or Negative review.

## Data Set Description
This data set is a 4 Million reviews collected from amazon website and divided into two fies:

   * Training File: 3.6 Million reviews
   * Testing File: 400 Thousands reviews

These two files have the same format   `Label Title : Review`

The dataset labled based on negativity or positivity of the review (There is no neutrality in the dataset).

It built using reviews with 1 or 2 stars and 4 or 5 stars:
    
   * `__Label__1` : 1 or 2 stars ==> Negative review
   * `__Label__2` : 4 or 5 stars ==> Positive review
   
**Also:** This dataset is a product category independent. (Books, Electronics, Food, DVDs, etc.)
### **Data set:** Kaggle [link](https://www.kaggle.com/bittlingmayer/amazonreviews)

## Project Objective

The objective of this project is to build a classifier using this data set to obtain high accuracy of classifying the sentiment of a product review, is it **positive** or **negative**

**Note:**
* This notebook `Capstone.ipynb` contains these steps:
    - Data reading
    - Data Cleaning 
    - Analytical plotting
    - Vectorizers:
        - Hashing Vectorizer n-grams(1,2):
            - Logistic Regression
            - Stochastic Gradient Descent Classifier
            - Linear Support Vector Classifier
        - Hashing Vectorizer n-grams(1,3):
            - Logistic Regression
            - Stochastic Gradient Descent Classifier
            - Linear Support Vector Classifier
        - Hashing Vectorizer no n-grams:
            - Logistic Regression
            - Stochastic Gradient Descent Classifier
            - Linear Support Vector Classifier
        - TF-IDF Vectorizer n-grams(1,2):
            - Logistic Regression
            - Stochastic Gradient Descent Classifier
            - Linear Support Vector Classifier
            - Deep Feed Forward Neural Network
    - Conclusion
    
    

* The Neural Network implementation for the Hashing Vectorizers are in other notebook `Cap-DNN.ipynb`
* Also, there is another notebook `Embedding.ipynb` for implementation of Pad Sequencer and Neural Network with Embedding Layer on the whole data `4 Million` Reviews

**Done By:** Yazan Alhroob