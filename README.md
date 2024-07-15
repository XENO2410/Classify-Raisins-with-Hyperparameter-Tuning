# Classify Raisins with Hyperparameter Tuning

## Project Overview

This project focuses on classifying different types of raisins using hyperparameter tuning methods. The dataset, provided by researcher Murat Koklu on Kaggle, includes two types of raisin grain (Kecimen and Besni) and seven numerical predictor variables for each of the 900 samples. The main objectives of this project are to:

1. Implement the Grid Search method to tune a Decision Tree Classifier.
2. Implement the Random Search method to tune a Logistic Regression Classifier.

## Data Description

The dataset consists of the following numerical predictor variables for each sample:

1. **Area**
2. **Perimeter**
3. **MajorAxisLength**
4. **MinorAxisLength**
5. **Eccentricity**
6. **ConvexArea**
7. **Extent**

The target variable is the raisin type, which can be either Kecimen or Besni.

## Project Steps

1. **Data Preprocessing**:
   - Load and explore the dataset.
   - Handle any missing values and normalize the input features if necessary.
   - Split the dataset into training and testing sets.

2. **Grid Search with Decision Tree Classifier**:
   - Implement a Decision Tree Classifier.
   - Perform hyperparameter tuning using Grid Search to find the optimal parameters.
   - Evaluate the performance of the tuned Decision Tree Classifier.

3. **Random Search with Logistic Regression Classifier**:
   - Implement a Logistic Regression Classifier.
   - Perform hyperparameter tuning using Random Search to find the optimal parameters.
   - Evaluate the performance of the tuned Logistic Regression Classifier.

4. **Comparison and Analysis**:
   - Compare the results of the two classifiers.
   - Analyze the effectiveness of Grid Search and Random Search in improving model performance.

## Conclusion

This project demonstrates the application of hyperparameter tuning techniques to classify different types of raisins. By using Grid Search and Random Search, the project aims to enhance the performance of Decision Tree and Logistic Regression classifiers.
