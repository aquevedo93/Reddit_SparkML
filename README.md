# Predictive Analysis using Reddit Comment Data and SparkML

Big Data data project using Reddit comment data from October 2018 to January 2019 (15 features and 433,521,422 observations) to develop predictive models to identify whether or not a a post is `stickied` or contains a `no_follow` link. 

* Stickied posts are posts that are highlighted and stay at the top of the subreddit (usually one or two posts)
* Nofollow links are those that don't allow search engine bots to follow them. 

Being classification problems, **Logistic Regression**, **Random Forest**, and **Gradient Boosted Tree** models were used including predictors reflecting post relevance, user involvement, and post characteristics. 

Spark was used throughout the different steps of the project given that it is performant in terms of running time and developer productivity (important since we are dealing with 500GB of data) and it enables iteration, which is essential to perform the machine learning tasks required in this assignment.


## Files Included

* `project_aq38.ipynb`: 
  - Data Cleaning 
  - Exploratory Data Analysis 
  - Data Visualization 
  - Machine Learning Models for each classification problem
  
* `Project.txt`: Writeup including analysis and future work
