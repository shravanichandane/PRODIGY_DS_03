# PRODIGY_DS_03
# Decision Tree Classifier for Bank Marketing Dataset
This repository contains an implementation of a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data using the Bank Marketing dataset from the UCI Machine Learning Repository.

# Dataset
https://archive.ics.uci.edu/static/public/222/bank+marketing.zip

# Requirements
Python 3.x </br>
pandas</br>
numpy</br>
matplotlib</br>
sklearn</br>

# Datapreprocessing
To use the decision tree classifier, follow these steps:

**- Download the Bank Marketing dataset from the UCI Machine Learning Repository and save it in the same directory as the code.** </br>
**- Run the code to load the dataset, preprocess the data, train the classifier, make predictions, and evaluate the performance of the classifier.**
# Code
***(The source code is given in respository)***</br>
The code is divided into three sections:

__Loading and preprocessing the dataset__
The dataset is loaded using pandas and preprocessed by dropping the 'deposit' column, encoding categorical variables using one-hot encoding, and splitting the data into training and testing sets.

__Training the classifier__
A decision tree classifier is created and trained on the training data using the fit method.

__Evaluating the performance of the classifier__
The classifier is used to make predictions on the testing data, and the accuracy of the classifier is calculated using the accuracy_score function from sklearn.metrics. The decision tree is also visualized using the plot_tree function from sklearn.tree.

__Generating classification report__
This report summarizes the performance of a decision tree classifier in predicting customer purchase behavior from demographic and behavioral data.

# Results
The accuracy of the classifier is printed out as the evaluation metric.
The decision tree classifier performed well in predicting customer purchases based on demographic and behavioral data. It had:

- **0.83 precision for no purchase and 0.71 precision for purchase**
- **0.68 recall for no purchase and 0.85 recall for purchase**
- **0.75 F1 score for no purchase and 0.77 F1 score for purchase**
- **Overall accuracy of 0.76**

The precision was better at predicting no purchases correctly, while the recall was higher for identifying actual purchases. The F1 scores, balancing precision and recall, were decent for both classes. With an overall accuracy of 0.76, this classifier shows promising performance in forecasting customer buying behavior from the given data features.

linkedin profile: www.linkedin.com/in/shravani-chandane-58ab062b6
