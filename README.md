# Badminton Tournament Scraper and Match Predictor

## Project Overview

This project involves scraping and analyzing badminton tournament data to predict match outcomes using machine learning. The primary goal is to forecast the probability that the higher-ranked player will lose a badminton match, in other words when an upset will occur.

## Phases

### Data Scraping

- **Collect data from the Badminton World Federation**: Extract match data, player rankings, and other relevant information from the BWF website.

### Data Processing

- **Clean and format data**: Filter out matches and data that are not relevant to the analysis or prediction model, standardize formats, and handle missing values to ensure a focused and clean dataset.
- **Feature engineering**: Incorporate player rankings and match statistics into the dataset to enhance analysis

### Match Prediction

- Apply RandomForestClassifier to historical data to predict match outcomes.
- **Evaluate and validate model performance**: Assess the accuracy of predictions and adjust model parameters as needed.

### Hyperparameter Tuning

- Systematically tune hyperparameters, such as the number of estimators and min samples split, to improve model accuracy.
- Perform a grid search to identify the optimal settings for the machine learning model.


