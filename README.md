# Diabetes_Prediction_using_Logistics_Regression_Modell
Diabetes Prediction using Logistic Regression
This repository contains a logistic regression model for predicting the presence of diabetes in individuals. The model utilizes a dataset obtained from the ybiFoundation/Dataset repository. The dataset consists of several independent variables such as age, glucose level, and more, with the target variable being the presence or absence of diabetes (Yes or No).

Dataset
The dataset used in this project has been preprocessed and split into training and testing data. It has been carefully curated and sourced from the ybiFoundation/Dataset repository, ensuring its quality and reliability.

Model Selection
The primary focus of this project is to develop a reliable model for diabetes prediction. Three different machine learning models have been implemented and evaluated: logistic regression, K-nearest neighbors (KNN), and random forest.

Logistic Regression
The logistic regression model, based on its underlying mathematical principles, is a suitable choice for binary classification problems like diabetes prediction. In our case, this model achieves an outstanding accuracy rate of 100% on the provided dataset. Logistic regression takes into account the relationships between independent variables and the probability of a specific outcome.

K-nearest Neighbors (KNN)
K-nearest neighbors (KNN) is a non-parametric classification algorithm that makes predictions based on the k closest neighbors in the feature space. In our experiments, the KNN model achieved an accuracy rate of 68% on the diabetes prediction task. This lower accuracy compared to logistic regression suggests that the underlying patterns in the dataset might not be easily captured by the KNN algorithm.

Random Forest
Random forest is an ensemble learning method that combines multiple decision trees to make predictions. It is known for its robustness and ability to handle complex relationships between variables. In our case, the random forest model achieves an accuracy rate of 100% on the diabetes prediction task, demonstrating its effectiveness in capturing the underlying patterns in the dataset.

Instructions
To use this repository, follow these steps:

Clone or download the repository to your local machine.
Ensure that the necessary dependencies are installed (e.g., Python, scikit-learn, etc.).
Open the provided Jupyter Notebook or Python script that contains the logistic regression model implementation.
Execute the code to train the logistic regression model on the provided training data.
Test the trained model on the provided testing data to evaluate its accuracy and performance.
Feel free to experiment with the different models implemented in this repository and explore further enhancements or modifications to improve the accuracy of the predictions.
