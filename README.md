# Fraud App Detection of Google Play Stores Using Decision Tree

## Overview

This project aims to detect fraudulent apps on the Google Play Store using a Decision Tree classification model. By analyzing various app features and metadata, the goal is to identify potentially fraudulent applications, thereby enhancing the security and reliability of the app marketplace.

## Features

- **Data Collection:** Collects app data including ratings, reviews, permissions, and other relevant features.
- **Preprocessing:** Cleans and prepares the data for analysis by handling missing values, encoding categorical variables, and scaling features.
- **Model Training:** Uses a Decision Tree classifier to train on the preprocessed data and predict fraudulent activity.
- **Evaluation:** Evaluates the performance of the Decision Tree model using metrics like accuracy, precision, recall, and F1-score.
- **Visualization:** Provides visualizations of model performance and data insights.

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib (for visualizations)
- seaborn (for visualizations)

You can install the necessary Python packages using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
