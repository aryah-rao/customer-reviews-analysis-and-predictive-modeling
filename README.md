# Data Analysis Projects

This repository contains two projects that showcase skills in data analysis, web scraping, sentiment analysis, and predictive modeling using Jupyter Notebooks. Each project highlights different stages of the data science process, from data collection to model training and evaluation.

## Projects Overview

### 1. Web Scraping and Analysis of Skytrax Data
- **Notebook:** `analysis.ipynb`
- **Description:** This project involves collecting customer reviews from the Skytrax website and analyzing them to gain insights into customer experiences with airlines. It includes:
  - **Web Scraping:** Using Python libraries such as `requests` and `BeautifulSoup` to gather customer reviews from the Skytrax website.
  - **Data Cleaning and Preprocessing:** Removing irrelevant text, emojis, and special characters to prepare the reviews for analysis.
  - **Sentiment Analysis and Exploratory Data Analysis (EDA):** Applying sentiment analysis to understand customer sentiment, visualizing the distribution of review categories, and identifying key aspects of customer satisfaction and dissatisfaction.

### 2. Hypertuning Predictive Modeling of Customer Bookings
- **Notebook:** `models.ipynb`
- **Description:** This project aims to predict whether a customer will complete their booking based on historical booking data. It covers the full pipeline of building a predictive model, including:
  - **Exploratory Data Analysis (EDA):** Exploring the dataset to uncover patterns, trends, and correlations between different features.
  - **Feature Engineering and Data Preparation:** Preprocessing data through scaling, encoding, and transforming features to make them suitable for machine learning models.
  - **Model Training and Hyperparameter Tuning:** Training two machine learning models—a neural network and an XGBoost classifier—using hyperparameter tuning to improve model performance.
  - **Evaluation and Interpretation:** Evaluating model performance on test data, and interpreting feature importance to understand which factors influence booking completion.

## Requirements

To run these notebooks, you will need Python and the necessary dependencies listed in the `requirements.txt` file.

You can install these dependencies using:
```bash
pip install -r requirements.txt
```