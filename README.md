# Churn-Telecom-Analysis

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on telecom churns from Kaggle Database. For detailed walkthrough, please view the source code from <a href="https://github.com/FeoniX97/Churn-Telecom-Analysis/blob/main/Predictive%20Modelling.ipynb">here</a>.

## Contributors
* @FeoniX97
* @jamalrasel

## Background
The telecom firm is experiencing a high rate of client turnover and is unable to pinpoint the cause. We'll create a comprehensive analysis report on the role of various factors in customer turnover, as well as a features-based forecasting
model. The predictive algorithm will be able to take company-provided services (fatures) as input and predict whether or not a customer
would churn in the future.
Based on input features, we want to build a model that can predict if a client would Churn or Retain (encoded as 0's and 1's). So, it
implies that we need to develop supervised classification model.

## Problem Definition
* Can we develop reliable prediction model for customer churn for the company?
We'll develop a detailed report of different accuracy metrics for the classification model
* Which model would be the best to predict it?

## Dataset
The <a href="https://github.com/FeoniX97/Churn-Telecom-Analysis/blob/main/datasets/Telecom_churn.csv">data</a> has rich, machine readable file format and metadata. We can observe in dataset that most of the features are numerical
datatype and data contain no missing values. So, it's a suitable data for analysis and devloping machine learing model.

## Models Used
* Logistic Regression
* Random Forest
* Support vector machines (SVM)
* K-nearest neighbors (KNN)

## Conclusion
* Boxplots are a better approach to show how features are distributed because we're working with bigger ranges and more continuous
characteristics.
* We can depict from the above plot that Churn feature has significant positive correlation with DayMins (0.21), CustServCalls
(0.21), IntlPlan (0.26) and DayCharge (0.21).
These features would be most significant predictors in developing a classification model for customer churn predictions.
* After optimising hyperparameters, the KNN model achieves the highest accuracy of 86.60 percent. By integrating more
relevant characteristics in the classification model and including more training data in the model, the predictive model's accuracy can be
further improved.

## References
* <a href="https://www.kaggle.com/mnassrib/telecom-churn-datasets">https://www.kaggle.com/mnassrib/telecom-churn-datasets</a>
* <a href="https://towardsdatascience.com/machine-learning-classifiers-a5cc4e1b0623">https://towardsdatascience.com/machine-learning-classifiers-a5cc4e1b0623</a>
* <a href="https://towardsdatascience.com/introduction-to-logistic-regression-66248243c148">https://towardsdatascience.com/introduction-to-logistic-regression-66248243c148</a>
* <a href="https://towardsdatascience.com/understanding-random-forest-58381e0602d2">https://towardsdatascience.com/understanding-random-forest-58381e0602d2</a>
* <a href="https://towardsdatascience.com/comparative-study-on-classic-machine-learning-algorithms-24f9ff6ab222">https://towardsdatascience.com/comparative-study-on-classic-machine-learning-algorithms-24f9ff6ab222</a>
