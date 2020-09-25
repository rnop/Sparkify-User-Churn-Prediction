# Sparkify User Churn Prediction

## Project Overview
### Motivation
A common challenge for data scientists is predicting customer churn. Understanding and predicting whether or not a user will churn is beneficial to the business because they can take actions to combat this and improve their business performance. Customer churn analysis also benefits the users because businesses will try to improve customer services and experiences based on insights gained from data science.

### Problem Statement
The goal of this project is to implement data-driven strategies to predict customer churn to improve business performance and customer experiences. Given the size of the full dataset, we will use a 128MB subset of it and perform our analysis on that using a standalone Spark framework.

### Python Libraries
* Python 3.7+
* Pyspark
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Datetime
* Time

### Sparkify.ipynb File
Contains the implementation, methodology, and analysis of data-driven strategies to predict customer churn of Sparkify users.

### Spark ML Models
* Logistic Regression
* Random Forest
* Gradient Boosting Classifier

### Results
Using the F1 score as our evaluation metric, the gradient boosting classifier performed the best with an F1 score of 0.801. The second best was the random forest with an F1 score of 0.779, and the third best was the logistic regression with an F1 score of 0.665.

### Improvements/Further Research
* More hyperparameter tuning step could be improved by trying out larger ranges of possible parameters. 
* Different feature selection and engineering
* Trying different machine learning models like NaiveBayesClassifier
* Using the full 12GB dataset might provide us better insights

### Acknowledgements
* Udacity
* Apache Spark
