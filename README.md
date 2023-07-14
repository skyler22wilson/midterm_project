# midterm_project

Lighthouse labs midterm project - Data Science intensive Bootcamp

## Project/Goals

- The goal is to define clear problems and to solve it in a way that will benefit the business needs.
- Acquisition of data for the purpose of answering the problem questions - Data Acquisition Phase
- Perform data cleaning to prepare data for EDA and modeling.
- Carry out Explorative Data Analysis to identify pattern and abnormalities in the data.
- Selecting, developing, learning and generalizing a Machine Learning algorithm to solve problems.
- Model validation and summary using metrics and statsmodel libraries.

## Process

Step 1- Discuss logistics, data sources and potential datasets of interest.

Step 2- Understand the information in the data. identify and state problems to sets objectives and guides the project.

Step 3- Performed data reformatting, cleaning and wrangling for analysis and modeling.

Step 4- Performed EDA and build different visualizations to learn about the dataset.

Step 5- Features and target selection to split data into training and testing sets.

Step 6- Building model using Surpervised Learning Models.

Step 7- Testing, predicting, validating and providing explanation for the model summary.

Step 8- Discuss on solutions to the problems stated and challenges faced during the project.

## Problem question

1) What are the determinant factors for the number of casualties in terrorist attacks?
2) What, if any were the determining factors in target selection for terror events?

# Results

1. The R-squared value for the model that determines what factors affect the number of casualties in terroris attacks was 45%. This suggests that only 45% of the variation in the independant variable (nkill) is explained by the dependant variables. However, the F statistic of 3434 and suggests that the dependent variables were significant predictors of the independent variable. Additionally the Log-likelihood of -1.999x10^5 suggests that the model does not fit the data well which emphasizes the results in the R-squared.
2. The R-squared value for the second model is only 14% this suggests taht the dependent variables only explain 14% of the variation in the independent variable (targtype1). Additionally the Log-likeilehood has a value of -1.89x10^5 whcih suggests a poor model fit. However, the F statistic of 138.2 suggests that the dependent variables are significant predictors of the independant variable. In other words this model suggests that the selection of target type for terror events is nearly random.

In both models, high correlation and multicolliniarity could have been major factors that affect model fit.

## Challenges

Although, the dataset provided alot of interesting features, but there were alot of missing values that limited our ability to provide robust analysis and modeling. Additionally, many variables were highly correlated which made fitting our models quite challenging. 

## Future Goals

Future goals will be to carry out additional research that can provide more detailed  information on events related to global terrorism which we could then use to improve our models and yeild more robust results. Additionally, we would also like to run a model on categorical variables such as the success of attacks using a random forest or generalized linear model.
