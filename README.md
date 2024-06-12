# Prodigy_DS_Task3

Bank Marketing Dataset Decision Tree Classifier
This project involves building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used is the Bank Marketing dataset from the UCI Machine Learning Repository. Below is a detailed explanation of the process:

Data Preprocessing
The data preprocessing step involves loading the dataset and handling any missing values. We encode categorical variables using Label Encoding to convert them into numerical values that can be used by the decision tree classifier. This ensures that all the features are in a format suitable for modeling.

Exploratory Data Analysis (EDA)
EDA is conducted to understand the dataset better. We visualize the distribution of the target variable (whether a customer will purchase the product or not) using count plots. Additionally, we plot the correlation matrix to identify relationships between different features, which helps in understanding the dataset's structure and the potential impact of each feature on the target variable.

Handling Class Imbalance
The dataset exhibits class imbalance, where the number of non-purchasers significantly outweighs the number of purchasers. To address this, we use upsampling of the minority class (purchasers) to balance the dataset. This step helps in improving the model's performance on the minority class.

Splitting the Data
The dataset is split into features (X) and the target variable (y). We further divide the data into training and testing sets to evaluate the model's performance on unseen data. This ensures that the model generalizes well to new data.

Building and Training the Model
We build a decision tree classifier using the training data. The decision tree is trained to learn the patterns and relationships between the features and the target variable. This step results in a model that can predict whether a customer will make a purchase based on their demographic and behavioral data.

Evaluating the Model
The trained model is evaluated on the test data to measure its performance. We calculate the accuracy and generate a classification report, which includes precision, recall, and F1-score for both classes (purchasers and non-purchasers). This step helps in understanding the model's effectiveness and areas for improvement.

Making Predictions on New Data
Finally, we demonstrate how to use the trained model to make predictions on new data. We create a sample dataset with the same structure as the training data, encode it using the same label encoders, and use the model to predict whether the customers will make a purchase. The predictions are then decoded to their original labels for interpretability.
