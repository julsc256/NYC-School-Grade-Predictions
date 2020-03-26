# Overview
___

The objective is to use the 2006-2007 school report to build a model that can predict a passing or failing grade of a school and interpret the results to find the factors which influence the grade.

___

## The Process

Supervised learning - Classification - allows us to tell if something belongs to one class, or the other. In this particular project, we're doing a multiclass classification problem because we're determining if the school will get a passing or failing grade.

## Dataset

- Combined enrollment information for each district via schooldigger.com and NYC Open Data: https://data.cityofnewyork.us/Education/2006-2007-School-Progress-Report/weg5-33pj

## Model Comparions

- KNN
- Decision Tree
- Random Forest
- Gradient Boost
- AdaBoost
- XGBoost

## Steps

1. Go through each model and find the f1 and accuracy score for both the train and test dataset.
2. Use accuracy score to determine best model and review the feature importance.
3. Test the models on new data (2007-2008 school year).
4. Review results.
___

# Results

Using all models, minus KNN, gave 98% to 99% accuracy.  When testing the models on new data, 14 out of 15 correct results.  

