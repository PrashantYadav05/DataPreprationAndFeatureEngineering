# Data preprations & Feature Engineering
The process of transforming raw data into a form that is more appropriate for modeling.

## Data imputation techniques:
* Removal of column varibales having only a single value.
* Consideration of column varibale with very few unique values.
* Rows that contains duplicate value.
* Performing mean or median imputation (replacing with mean  if normally distributed otherwise median,  may distort the distribution if high percentage of missing data is present)
* Implementing mode or frequent category imputation ( If the percentage of missing values is high may distort the original distribution of categories) 
* Replacing missing values with an arbitrary number(when data is not missing at random, while building non-linear models, may distort the distribution if high percentage of missing data is present)
* Capturing missing values in a bespoke category.
* Replacing missing values with a value at the end of the distribution (End-of-tail imputation may distort the distribution of the original
variables may not be suitable for linear models)
* Implementing random sample imputation(Preserves the original distribution)
* Adding a missing value indicator variable.
* Performing multivariate imputation by chained equations.
* Assembling an imputation pipeline with scikit-learn.
* Assembling an imputation pipeline with Feature-engine

## Encoding techniques:
* Creating binary variables through one-hot encoding (When determining the importance of each category within a variable, when training decision trees)
* Performing one-hot encoding of frequent categories,
* Replacing categories with ordinal numbers.
* Replacing categories with counts or frequency of observations.
* Encoding with integers in an ordered manner.
* Encoding with the mean of the target.
* Encoding with the Weight of Evidence.
* Grouping rare or infrequent categories.
* Performing binary encoding.
* Performing feature hashing.
## Outlier Handling methods
* Trimming outliers from the dataset
* Performing winsorization
* Capping the variable at arbitrary maximum and minimum values
* Performing zero-coding – capping the variable values at zero


Winsorizer
ArbitraryOutlierCapper

Discretisation methods
EqualFrequencyDiscretiser
EqualWidthDiscretiser
DecisionTreeDiscretiser
ArbitraryDiscreriser

## Variable transformation methods:
* Transforming variables with the logarithm.
* Transforming variables with the reciprocal function.
* Using square and cube root to transform variables.
* Using power transformations on numerical variables.
* Performing Box-Cox transformation on numerical variables.
* Performing Yeo-Johnson transformation on numerical variables.




LogTransformer
LogCpTransformer
ReciprocalTransformer
PowerTransformer
BoxCoxTransformer
YeoJohnsonTransformer
Scikit-learn Wrapper:
SklearnTransformerWrapper
Variable Creation:
MathematicalCombination
CombineWithReferenceFeature
CyclicalTransformer


## Performing variable "Discretization":
* Dividing the variable into intervals of equal width
* Sorting the variable values in intervals of equal frequency
* Performing discretization followed by categorical encoding
* Allocating the variable values in arbitrary intervals
* Performing discretization with k-means clustering
* Using decision trees for discretization

## Feature Selection: 
Feature selection methods are intended to reduce the number of input variables to those that are believed to be most useful to a model in order to predict the target variable.

* Mutual Information Feature Selection: Mutual information is calculated between two variables and measures the reduction in uncertainty for one variable given a known value of the other variable.
* Numerical input data and a categorical (class) target variable (ANOVA F-Statistic, Mutual Information Feature Selection)
* Numerical input data and a numerical target variable (Correlation Statistics, Mutual Information Statistics)
* How to Use RFE for Feature Selection.
* Feature importance:Feature importance refers to techniques that assign a score to input features based on how useful they are at predicting a target variable.

## Deriving Features from Dates and Time Variables:
* Extracting date and time parts from a datetime variable
* Deriving representations of the year and month
* Creating representations of day and week
* Extracting time parts from a time variable
* Capturing the elapsed time between datetime variables
* Working with time in different time zones

## Performing Feature Scaling:
* Standardizing the features
* Performing mean normalization
* Scaling to the maximum and minimum values
* Implementing maximum absolute scaling
* Scaling with the median and quantiles
* Scaling to vector unit length

## Working with Outliers:
* Trimming outliers from the dataset
* Performing winsorization
* Capping the variable at arbitrary maximum and minimum values
* Performing zero-coding – capping the variable values at zero

## Dimesionality reduction:
* How to Perform SVD Dimensionality Reduction
