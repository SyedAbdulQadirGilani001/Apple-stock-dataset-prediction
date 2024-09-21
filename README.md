# Stock Prediction using Machine Learning


Table of Contents

1. # introduction
2. ## features
3. ### functionality
4. #### technical-requirements
5. ##### installation
6. ###### usage
7. models
8. performance-metrics
9. visualization
10. conclusion

## Introduction


This project uses machine learning to predict stock prices. We'll explore four models: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.


### Features


- Loads Apple stock data from Yahoo Finance
- Creates target variable (up or down) based on stock price movement
- Scales data using Min-Max and Z-Score scaling
- Trains and evaluates four machine learning models
- Plots performance metrics and model comparisons


#### Functionality


1. Data Loading: Loads Apple stock data from Yahoo Finance.
2. Target Variable Creation: Creates target variable (up or down) based on stock price movement.
3. Data Scaling: Scales data using Min-Max and Z-Score scaling.
4. Model Training: Trains four machine learning models.
5. Model Evaluation: Evaluates model performance using accuracy, precision, recall, f1-score, and support.
6. Visualization: Plots performance metrics and model comparisons.


##### Technical Requirements


- Python 3.x
- yfinance
- pandas
- scikit-learn
- plotly


##### Installation



**bash**
***pip install yfinance pandas scikit-learn plotly***



Usage


1. Clone the repository.
2. Run python 


##### Models


1. Logistic Regression: A linear model for binary classification.
2. Decision Tree: A tree-based model for classification.
3. Random Forest: An ensemble model combining multiple decision trees.
4. Gradient Boosting: An ensemble model combining multiple weak learners.


##### Performance Metrics


- Accuracy: Proportion of correct predictions.
- Precision: Proportion of true positives among positive predictions.
- Recall: Proportion of true positives among actual positive instances.
- F1-score: Harmonic mean of precision and recall.
- Support: Number of instances in each class.


##### Visualization


- Scatter Matrix: Plots relationships between features.
- Stock Price: Plots Apple stock price over time.
- Volume Distribution: Plots volume distribution by target variable.
- Model Accuracy Comparison: Plots accuracy comparison among models.


##### Conclusion

This project demonstrates the application of machine learning in stock price prediction. Gradient Boosting performed best with an accuracy of 0.90.
