# CostaRicaPovertyPrediction

### Objective:

Use classification to identify which households have the highest need for social welfare assistance.

### Motivation: 

Social programs have a hard time directing enough aid to people that need it. It’s especially tricky when a program focuses on the poorest segment of the population. In Latin America, one popular method uses an algorithm to verify income qualification, known as the Proxy Means Test (or PMT). This allows agencies to use a model that considers a family’s observable household attributes like the material of their walls and ceiling, or the assets found in the home to classify them and predict their level of need.  While this is an improvement, accuracy remains a problem as the region’s population grows and poverty declines.

### Variables:
There are roughly 142 variables describing each entry for the row. Some interesting variables for easy approaching classification would be

idhogar - a unique identifier for each household. This can be used to create household-wide features, etc. All rows in each household will have a matching value for this identifier.

parentesco1 - indicates if this person is the head of the household.

Target - the target is an ordinal variable indicating groups of income levels. 
  1 = extreme poverty
  2 = moderate poverty
  3 = vulnerable households
  4 = non-vulnerable households 

### Methods:

Exploratory Data Analysis - on variables including but not limited to distribution of age, target variables, materials in homes, conditions of the homes

Classification – Apply various models including but not limited to Logistic Regression, XGBoosted, Decision Trees, Random Forest, KNN. Evaluation on the models with be done with doing ROC Curves, Confusion Matrixes, and Variable Importance



