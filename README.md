# LinearRegressionPy
Linear Regression was performed to examine the auto.csv file.

CourseWorks for Supervised ML under Prof Nachiketa Sahoo, Boston University

FYI column definitions (from https://cran.r-project.org/web/packages/ISLR/ISLR.pdf):

mpg: miles per gallon (The outcome, or y, variable)
cylinders: Number of cylinders between 4 and 8
displacement: Engine displacement (cu. inches)
horsepower: Engine horsepower
weight: Vehicle weight (lbs.)
acceleration: Time to accelerate from 0 to 60 mph (sec.)
year: Model year (modulo 100)
origin: Origin of car (1. American, 2. European, 3. Japanese)
name: Vehicle name


Questions involved 
1. Should you drop any variable from regression analysis and why?
2. Which variables should be treated as numeric and which as categorical? Explain why.
3. Plot all the pairwise scatter plots and histograms for the numeric features.
4. Discuss two interesting relationships that you notice.
5. Compute the correlation matrix among the numeric variables. Discuss one interesting correlation.
6. Use statsmodels to regress mpg on all other variables. Note you can tell ols() to treat a variable as categorical by enclosing the variable in C().
7. From the above regression model, include two way interactions between a numeric and categorical variable in three different regression models (three separate models in total). Do any of them appear significant? Discuss the results.
8.Measure the in-sample and out of sample  𝑅2  of the model estimated in Q4.1 using 20% data for testing.

