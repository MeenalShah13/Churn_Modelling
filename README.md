# Churn_Modelling
Using Customer Characteristics to predict Account Retention (Data Analytics)

What is churn modelling?
A churn model is a mathematical representation of how a churn impacts one 's  business.It Predicts the set of the customers that are going to churn out from the organization by looking into some of the existing attributes and applying Machine Learning models on it. A predictive churn model extrapolates on this data to show future potential churn rates.A Predictive Churn Model is a tool that defines the steps and stages of customer churn, or a customer leaving your service or product.

The given dataset is about the customers who has credit account in bank and whether they have churned out or not. By using this dataset we can predict churn rate using different machine learning models that whether the given customer is about to churn out or not.

Our Approach:
1. Data exploration : It is a initial step in data analysis. Analysts use data visualization and statistical techniques to describe dataset characterizations, such as size, quantity, and accuracy, in order to better understand the nature of the data.
2. Data cleaning : Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect, incomplete, irrelevant, duplicated, or improper.
3. Data visualisation : Data visualization is the act of taking information (data) and placing it into a visual context, such as a map or graph. Data visualizations make big and small data easier for the one to understand
4. Data preprocessing : In any Machine Learning process, Data Preprocessing is that step in which the data gets transformed, or Encoded, to bring it to such a state that now the machine can easily parse it. In other words, the features of the data can now be easily interpreted by the algorithm.
5. Splitting of dataset into training and testing dataset : It is a fast and easy procedure to perform, the results of which allow you to compare the performance of machine learning algorithms for your predictive modeling problem. 
6. Build machine learning models using training dataset : The process of training an ML model involves providing an ML algorithm (that is, the learning algorithm) with training data to learn from.
7. Test the model using testing dataset : The process of validating model using test dataset to check the accuracy of the model.
8. Find accuracy for each model and compare them : Last step was to calculate the accuracy of each predictive model and  to find the best predictive model for our dataset by compairing accuracy of each.

Machine learning models used for the prediction are:

1. Random Forest : The random forest is a classification algorithm consisting of many decisions trees. It uses bagging and feature randomness when building each individual tree to try to create an uncorrelated forest of trees whose prediction by committee is more accurate than that of any individual tree.

2. Logistic Regression : Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable.

3. k-nearest neighbors : K nearest neighbors is a simple algorithm that stores all available cases and classifies new cases based on a similarity measure.

4. Naive Bayes : Naive Bayes classifiers are a collection of classification algorithms based on Bayes' Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other.

Accuracy is calculated for each of these models to find the best model for the prediction.We can conclude that Logistic Regression is best predictive model among all with accuracy of 86.4%.
