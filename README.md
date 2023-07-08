# Wine-Quality-Prediction
Predicting the quality of red wine using different classification algorithms

## Dataset
This project will predict the red wine samples' quality from Kaggle's [Red Wine Quality](http://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009) dataset. Each wine in this dataset is given a “quality” score between 0 and 10. For this project, I converted the output to a binary output where each wine is either “good quality” (a score of 7 or higher) or not (a score below 7). The quality of a wine is determined by 11 input variables:
```
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
12. quality (score between 0 and 10)
```
<br>

## Classification 
I'll use 7 classification algorithms and then, find the best-performing algorithm out of the lot.
<br>
The algorithms which I'll be using are:

```
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)
- Decision Tree
- Gaussian Naive Bayes (GaussianNB)
- Random Forest 
- XGBoost
```

I will compare the performance of these algorithms based on their accuracy scores to select the best-performing one. For certain algorithms with hyperparameters that can take on different values, such as the n_neighbors in KNN or the n_estimators in Random Forest, I will evaluate multiple combinations of hyperparameter values.

I will calculate the accuracy scores for each combination of hyperparameters and select the one with the highest accuracy. Once the best-performing hyperparameter value is determined for each algorithm, I will compare the algorithms based on their corresponding best accuracy scores. This way, I can identify the algorithm that provides the highest accuracy on the given dataset.

<br>

## Libraries/concepts used
```
- Pandas
- Numpy
- matplotlib
- seaborn
- sklearn (scikit-learn)
- Classification algorithms
- Naive Bayes classifier
- Extreme Gradient Boosting
```
