# IE-2064 Competition - Group 1

This project is a collaborated competition based on the dataset from [PittDataScience/CourseContent](https://github.com/PittDataScience/CourseContent/tree/master/Assignments/competition)

## Description

**This project contains 3 main parts:**

* The training and testing dataset
* The code of how we train our model
* The prediction of outcome

## Brief summary for the files

* [competion-data.csv](https://github.com/clewandowski9/Competition/blob/main/competition-data.csv) : Trianing dataset which is provided by professor Hinder
* [competition-test-x-values.csv](https://github.com/clewandowski9/Competition/blob/main/competition-test-x-values.csv) : Test dataset without outcome, our target is predicting the outcome via our model
* [competition-code-group 1.Rmd](https://github.com/clewandowski9/Competition/blob/main/competition-code-group%201.Rmd) : The code of model training which includes following content
  + Data exploration
  + Data preprocessing (feature engineering)
  + Multi model fitting and training
  + Error evaluating for each model
  + Prediction of unseen data (competition-test-x-values) generating
* [competition-model-accuracy-verification.Rmd](https://github.com/clewandowski9/Competition/blob/main/competition-model-accuracy-verification.Rmd) : In order to make sure the model will work well, we separated **competion-data.csv** into training and test set, then we can estimate what RMSE we may get if we applied the model on unseen data.
* [competition-test-outcome.csv](https://github.com/clewandowski9/Competition/blob/main/competition-test-outcome.csv) : Final prediction of outcome (1 column dataframe)


## Authors

Contributors names and contact info

* **Group 1**
  + Sheng-Yu Wei / [ShengY1995](https://github.com/ShengY1995) 
  + Christian Lewandowski / [clewandowski9](https://github.com/clewandowski9)
