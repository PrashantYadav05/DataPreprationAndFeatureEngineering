# Data preprations & Feature Engineering
Current Feature-engine's transformers include functionality for:
* **Missing Data Imputation**
* **Categorical Variable Encoding**
* **Outlier Capping or Removal**
* **Discretisation**

## Data imputation techniques:
* Removal of column varibales having only a single value.
* Consideration of column varibale with very few unique values.
* Rows that contains duplicate value.
* Performing mean or median imputation.
* Implementing mode or frequent category imputation.
* Replacing missing values with an arbitrary number.
* Capturing missing values in a bespoke category.
* Replacing missing values with a value at the end of the distribution.
* Implementing random sample imputation.
* Adding a missing value indicator variable.
* Performing multivariate imputation by chained equations.
* Assembling an imputation pipeline with scikit-learn.
* Assembling an imputation pipeline with Feature-engine

## Encoding techniques:
* Creating binary variables through one-hot encoding.
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
Winsorizer
ArbitraryOutlierCapper
OutlierTrimmer
Discretisation methods
EqualFrequencyDiscretiser
EqualWidthDiscretiser
DecisionTreeDiscretiser
ArbitraryDiscreriser
## Variable Transformation methods
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
## Feature Selection:
DropFeatures
DropConstantFeatures
DropDuplicateFeatures
DropCorrelatedFeatures
SmartCorrelationSelection
ShuffleFeaturesSelector
SelectBySingleFeaturePerformance
SelectByTargetMeanPerformance
RecursiveFeatureElimination
RecursiveFeatureAddition
