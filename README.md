**Complaint Classification using NLP**

Overview

This project focuses on building a Natural Language Processing (NLP) pipeline to automatically classify customer financial complaints into predefined service categories. The solution leverages machine learning techniques to process unstructured text data and assign each complaint to the appropriate business segment.

Automating complaint categorization enables faster resolution workflows, improved analytics, and better customer experience management.

**Problem Statement**

Financial institutions receive large volumes of customer complaints in free-text format. Manually reviewing and categorizing these complaints is time-consuming and inefficient.

This project develops a text classification system capable of categorizing complaints into the following service areas:

Credit Card / Prepaid Card

Bank Account Services

Theft / Dispute Reporting

Mortgages / Loans

Others

**Solution Approach**

The project follows a structured NLP pipeline:

**1. Data Preprocessing**

Cleaning

Tokenization and normalization

Stopword removal

Lemmatization/Stemming

**2. Exploratory Data Analysis (EDA)**

Class distribution analysis

Word frequency analysis

N-gram exploration

Text length distribution

**3. Topic Modeling**

Latent Dirichlet Allocation (LDA) used to identify underlying themes in complaints  

Extracted dominant topics across categories  

Evaluated topic coherence scores  

Used topic distributions to better understand complaint clusters  

**4. Feature Engineering**

Bag of Words (BoW)

TF-IDF Vectorization

(Optional) Word Embeddings

**5. Model Development**

Traditional Machine Learning models (e.g., Logistic Regression, Naive Bayes, SVM)

Model comparison and evaluation

Hyperparameter tuning

**6. Evaluation Metrics**

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

**Results**

The final model demonstrates strong performance in classifying financial complaints across multiple categories. Performance improvements were achieved through preprocessing optimization and feature engineering techniques.
