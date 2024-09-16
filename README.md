# Badminton Tournament Scraper and Match Predictor

## Project Overview

This project involves scraping and analyzing badminton tournament data to predict match outcomes using machine learning. The primary goal is to forecast the probability that the higher-ranked player will lose a badminton match, in other words when an upset will occur.

## Phases

### 1. Data Scraping

- **Collect data from the Badminton World Federation**: Extract match data, player rankings, and other relevant information from the BWF website.

### Data Processing

- **Clean and format data**: Remove unnecessary or corrupted data, standardize formats, and handle missing values.
- **Enrich data with player rankings and match statistics**: Integrate player ranking data and other match statistics into the dataset for enhanced analysis.

### Match Prediction

- **Use machine learning models**: Apply RandomForestClassifier to historical data to predict match outcomes.
- **Evaluate and validate model performance**: Assess the accuracy of predictions and adjust models as needed.

### Hyperparameter Tuning

- **Optimize model performance**: Systematically tune hyperparameters, such as the number of estimators and min samples split, to improve model accuracy.
- **Use grid search for best parameters**: Perform a grid search to identify the optimal settings for the machine learning model.


