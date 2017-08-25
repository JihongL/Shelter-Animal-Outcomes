## Shelter Animal Outcomes
- Kaggle compitition of Austin Animal Center
- www.kaggle.com/c/shelter-animal-outcomes
- 838th on Public leaderboard (log loss 0.86108)
- Multiclass classification

### Introduction
- [Shelter_EDA](http://nbviewer.jupyter.org/github/JihongL/Shelter-Animal-Outcomes/blob/master/Shelter_EDA.ipynb)
  - Preprocessing
  - Graphworks
- [Shelter_Classification](http://nbviewer.jupyter.org/github/JihongL/Shelter-Animal-Outcomes/blob/master/Shelter_Classification.ipynb)
  - Apply classification model
  - Submit

### Workflow
|EDA &<br>Preprocessing|Model<br>Selection|Model<br>Validation|
|:---:|:---:|:---:|
|Dummification<br>Data Cleaning|Feature Selection<br>Cross Validation|logloss|

### Dataset
- Animal outcome data from October 1st, 2013 to March, 2016

|Set|Rows|Columns|
|:---:|:---:|:---:|
|Train|26730|10|
|Test|11457|8|

#### Independent Values
|Index|Values|Type|Description|
|:---:|:---:|:---:|:---|
|1|AnimalID|Category|Unique ID for each animal|
|2|Name|Category|Each animal's name. if not have, NaN|
|3|DateTime|Numeric|Time when outcome occurs|
|4|AnimalType|Category|2 variables|
|5|SexuponOutcome|Category|5 variables|
|6|AgeuponOutcome|Numeric|The age of animals|
|7|Breed|Category|1380 variables|
|8|Color|Category|366 variables|

#### Dependent Values
|Index|Values|Type|Description|
|:---:|:---:|:---:|:---|
|1|OutcomeType|Category|5 variables|
|2|OutcomeSubtype|Category|16 variables|
