# titanic-dataset

 This is my first submission to Kaggle competition Titanic Machine Learning From Disaster. It was made by studying of some guides across the internet, which in grateful for the efforts to compile these guides.

 ## The score

 I obtained a 0.76794, which means i should improve more my models.


## The Challenge (From Kaggle Website)
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

### Data Description (From Kaggle Website)


  *  Survival: 0 = Did not survive, 1 = Survived
  *  Pclass: Ticket class where 1 = First class, 2 = Second class, 3 = Third class. This can also be seen as a proxy for socio-economic status.
  *  Sex: Male or female
  *  Age: Age in years, fractional if less than 1
  *  SibSp: Number of siblings or spouses aboard the titanic
  *  Parch: Number of parents or children aboard the titanic
  *  Ticket: Passenger ticket number
  *  Fare: Passenger fare
  *  Cabin: Cabin number
  *  Embarked: Point of embarkation where C = Cherbourg, Q = Queenstown, S = Southampton

### Dependencies

* Numpy
* Pandas
* Matplot
* Seaborn
* Sklearn
* Catboost

### The notebook

The notebook is available for you to check and see everything that was done. I divided the as:

#### Load packages and dataset

Import python packages and load the datasets to train and test in the Jupyter Lab. At this point i dropped the columns Ticket and Cabin.

#### Exploratory Data Analysis

Checked every feature and started handling some of them, as encoding the categorical features.

#### Data handling

At this point i handled the Nan of the Age column and corrected the Skewness from Fare.

#### Feature Engineering

Created new feature Title, converted Fare and Age to categorical features, and lastly made a flag for family (IsAlone).

#### Model training and submission

The final step was to study the models, fit the data, hyperparameters tunning and the prediction to submit the data.
