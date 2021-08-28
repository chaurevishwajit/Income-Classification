# Income-Classification

## Goal
To classify whether income exceeds $50K/yr based on census data.

## Variable List

* age: continuous
* workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
* fnlwgt: continuous.
* education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
* education-num: continuous.
* marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
* occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport- moving, Priv-house-serv, Protective-serv, Armed-Forces.
* relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
* race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
* sex: Female, Male.
* capital-gain: continuous.
* capital-loss: continuous.
* hours-per-week: continuous.
* native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

## Data Modelling Steps Performed
* Build a classification model to classify whether the income exceeds $50K/yr
* Performed data cleaning to handle missing values, and ensure datatype consistency
* Conducted exploratory data analysis
* Built a data pipeline with the following components
  * If applicable used scalers (min max, standardize, normalize) for numerical variables
  * If applicable reduced the number of factors for categorical predictors
  * Models used (logistic, naive bayes, decision trees, kNN, and neural network)
  * Performed hyperparameter tuning and reported all the different model combinations
  * Compared the performance of different models and selected the best model along with the best model parameters
* Tried hold out method or cross validation method for training
* Perfomed variable selection procedure (forward, backward) to select the best predictors 

## Dataset
Used the [Train_data](Train_data.csv) to train the models
Used [Test_data](Test_data.csv) to test the models
