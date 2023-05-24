# Seasonal Flu Machine learning Prediction_model
* A prediction Model of Season Flu Vaccine uptake

![Vaccine](https://content.presspage.com/uploads/2110/1920_potsvaccination.jpeg?10000)
## Introduction
* This study aims to create a prediction model to anticipate whether or not people will get a flu shot during the annual flu season.

* The flu season occurs on an annual basis, and each year people choose whether or not to get the flu shot.

* The model should leverage historical data to identify patterns and factors that influence people's vaccination choices.

## Main Ojectives
* To grasp the statistical implications of variables such as age groups, genders, and the existence of children in homes and analyze them.

* Respond to enquiries about targeting certain subsets of the population to increase overall immunization rates

* Excluding any specified aims, investigate the factors influencing individuals' decision to obtain the flu vaccination during the annual flu season.

* Create a predictive model to forecast whether or not people will receive the  Flu Vaccine based on particular characteristics or conditions.

## Data Description
* The dataset used for this project was downloaded from Kaggle.

* It contains information on the social,economic and demographic backgrounds of the respondents as well as their opinions on the H1N1 and seasonal flu vaccines.

* The training data has 26707 rows and 36 columns.

## Data Preperation
* The data was assessed and exploratory data analysis (EDA) was carried out after it had been loaded in order to comprehend the dataset better. 

* It was discovered that there were several missing values during this process, and these were fixed by substituting suitable values for them.

* Since the dataset's features are all categorical, their data types were changed to make ordinal encoding easier. 

* The data needed to be transformed in order to be ready for modeling.

## Data Modelling
* The training and test datasets were created from the data. Decision Tree was used to build the baseline model.

* XGBoosting, ADABoosting, RandomForest and GradientBoostingClassifier were employed.

## Model evaluation
* The model selection was based on the following criteria:

- Potential to learn from more data and not be at risk of over-fitting.
- Accuracy and ability to generalize over unseen data.

## conclusions
* The gradient boosting model was optimal despite existing biases within our features.

* The data set was biased towards certain communities and classes.

* This makes the models generated biased towards this group of people and may not reflect the general situation.

* The data should be better sampled to avoid biases and ensure that all groups are adequately represented, and it would benefit from more data since accuracy increased as more data was submitted.

## Recommendations
* Careful examination of the significance of identified predictors, such as opinion_seas_risk, will help understand underlying factors and ensure fairness in decision-making

*  According to the models, people's opinions have a significant impact on their chance to take immunizations. Given this, the following suggestions can be made:

*  Campaigns should be launched to raise public knowledge about the effectiveness of the seasonal flu vaccine as well as the hazards connected with the virus.

*  It would be beneficial to emphasize the safety of the vaccines for public use.

*  The seasonal flu vaccine is more likely to be used by older persons. The younger population could, therefore, be targeted for such campaigns.

* To ensure better data gathering, a broader range of demographic groups should be included, resulting in a more diverse and balanced dataset.

* It is recommended to validate conclusions by combining external data from diverse sources to improve generalizability.

* Techniques like as oversampling, undersampling, or the use of weighted loss functions can be used to reduce biases during the model training process.# Seasonal-Flu-Vaccine-Project
