# Decode 10.3 Hackathon
## Organised by Board Infinity 

### Problem Statement

Examine the dataset provided, perform EDA. Finally, for the given test dataset, predict whether an individual’s income will begreater than $50,000 per year based on several attributes from the census data.

### Data

The dataset provided has 32724 entries in the train dataset, and 9000 entries in the test dataset. 

Each entry contains the following information about an individual:
* **age**: the age of an individual
    * Integer greater than 0
* **workclass** : a general term to represent the employment status of an individual
    * Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov,Without-pay, Never-worked.
* **fnlwgt**: final weight. In other words, this is the number of people the census believes the entry represents.
    * Integer greater than 0
* **education**: the highest level of education achieved by an individual.
    * Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc,9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
* **education-num**: the highest level of education achieved in numerical form.
    * Integer greater than 0
* **marital-status**: marital status of an individual. Married-civ-spouse corresponds to a civilian spouse while Married-AF-spouse is a spouse in the Armed Forces.
    * Married-civ-spouse, Divorced, Never-married, Separated, Widowed,Married-spouse-absent, Married-AF-spouse.
* **occupation**: the general type of occupation of an individual
    * Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical,Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
* **relationship**: represents what this individual is relative to others. For example an individual could be a Husband. Each entry only has one relationship attribute and is somewhat redundant with marital status. We might not make use of this attribute at all. 
    * Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
* **race**: Descriptions of an individual’s race
    * White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
* **sex**: the biological sex of the individual
    * Male, Female
* **capital-gain**: capital gains for an individual 
    * Integer greater than or equal to 0
* **capital-loss**: capital loss for an individual
    * Integer greater than or equal to 0
* **hours-per-week**: the hours an individual has reported to work per week
    * continuous.
* **native-country**: country of origin for an individual
    * United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam,USVI,etc), India, Japan, Greece, South, China, Cuba, Iran,Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal,Ireland, France, Dominican Republic, Laos, Ecuador, Taiwan, Haiti, Columbia,Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
* **net-income**: whether or not an individual makes more than $50,000 annually.
    * <=50k, >50k


For insights, EDA, model selection, please go through the detailed explanation in `HackathonCensusIncome.ipynb` file. 

**Submitted by**-
Sarvjeet Kour
DS21JAN04 
