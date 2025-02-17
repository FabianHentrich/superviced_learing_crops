# Crop Suitability Analysis: Machine Learning for Agricultural Optimization

## Project Overview

This project aims to identify the optimal soil conditions for crop growth by evaluating the predictive power of key soil nutrients (N, P, K) and pH levels. The goal is to understand how these soil characteristics influence crop suitability and to provide valuable insights for agricultural planning.

## Methodology

1. **Data Collection**:
   - Soil data was gathered for various agricultural fields, including concentrations of nitrogen (N), phosphorus (P), potassium (K), and pH levels.

2. **Feature Selection**:
   - Relevant features such as N, P, K, and pH were selected to determine the influence of these factors on crop growth.

3. **Logistic Regression Model**:
   - A logistic regression model was used to classify the crop suitability into binary categories (suitable vs. unsuitable).

4. **Performance Metrics**:
   - The **F1 score** was used as the primary evaluation metric to balance precision and recall for optimal crop suitability prediction.

## Results

The logistic regression model highlighted the following insights:
- Key soil nutrients (N, P, K) and pH levels are predictive of crop growth success.
- The optimal thresholds for each nutrient varied slightly depending on the crop type, but an overall pattern emerged that allowed for strong predictions of suitability.
- Using all features combined led to an **F1 score of 0.65**.

## Disclaimer

This project is for demonstration and educational purposes only. The results should not be interpreted as professional agricultural advice.

 
