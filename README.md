## Tree Classifier for Bank Marketing Campaign
This repository contains an implementation of a decision tree-based classification model to predict the outcome of a bank marketing campaign. The project uses data from a Portuguese banking institution to determine if a client will subscribe to a term deposit.

## Files
tree-classifier.ipynb

A Jupyter Notebook implementing and analyzing classification models.
Features data preprocessing, exploratory data analysis (EDA), and decision tree classification.
bank.csv

A smaller dataset with 10% of the full dataset's records (4,521 instances).
Suitable for testing computationally expensive algorithms.
bank-full.csv

The complete dataset containing 45,211 instances.
Includes client attributes, campaign details, and the classification target.
bank-names.txt

Documentation for the datasets, including attribute descriptions and relevant citations.
## Dataset Details
The data relates to direct marketing campaigns conducted via phone calls. The goal is to predict if a client will subscribe to a term deposit (y = "yes" or "no") based on various features:

Input Variables:
Client demographic and campaign-related information (e.g., age, job, marital status, contact type, etc.).
Output Variable:
y - Subscription outcome (binary: "yes" or "no").
## Key Files
bank.csv: A subset of the full dataset for initial exploration and testing.
bank-full.csv: Full dataset with detailed campaign results.

## Project Highlights
Exploratory Data Analysis (EDA):
Visualizations and summary statistics to understand the dataset.
Modeling:
Uses decision trees to classify client responses based on campaign data.
Performance Metrics:
Evaluates models using accuracy, precision, recall, and F1-score.
## Usage
This project can be used to:

Understand decision tree models for classification tasks.
Analyze marketing campaign data for predictive insights.
Explore client segmentation and predictive modeling in financial services.
