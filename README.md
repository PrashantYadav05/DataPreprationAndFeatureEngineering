# Feature Engineering
Current Feature-engine's transformers include functionality for:
* **Missing Data Imputation**
* **Categorical Variable Encoding**
* **Outlier Capping or Removal**
* **Discretisation**

## Data imputation techniques:
* Removal of column varibales having only a single value.
* Consideration of column varibale with very few unique values.
* Rows that contains duplicate value.
MeanMedianImputer
RandomSampleImputer
EndTailImputer
AddMissingIndicator
CategoricalImputer
ArbitraryNumberImputer
DropMissingData
## Encoding Methods
OneHotEncoder
OrdinalEncoder
CountFrequencyEncoder
MeanEncoder
WoEEncoder
PRatioEncoder
RareLabelEncoder
DecisionTreeEncoder
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
