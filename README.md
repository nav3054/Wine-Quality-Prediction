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
Out of these algorithms, I'll choose the best-performing algorithm by comparing their accuracy scores. For some algorithms, which can have different values for different hyperparameters (such as n_neighbors in KNN and n_estimators in Random Forest), different values of the hyperparameters will be compared with each other. Then, the hyperparameter with the highest accuracy score will be selected and the algorithm will be assigned the accuracy score of the best-performing hyperparameter value. Only after the best possible accuracy scores of all the algorithms have been calculated will the comparison of algorithms begin.

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
```
