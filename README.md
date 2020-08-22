# Titanic-Survival-Prediction-Using-ML-Algorithms

**-This is a binary classification to detect the survival or death of a passenger onboard the Titanic. The model predicts the death or survival of a new passenger._**

TITANIC SURVIVAL PREDICTION

**Ritam Chowdhury**

**6th August 2020.**

**Goal**

Using various ML algorithms I have tried to
predict the survival or the death of a given passenger based on 12 feature such as
sex, age, etc.


**Software and Libraries**

This project uses the following software and Python libraries:

- Python 3.8
- Anacoda IDE
- NumPy
- pandas
- matplotlib
- seaborn 
- sklearn
- Jupyter


**Introduction:**
RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early hours of 15 April
1912, after colliding with an iceberg during its maiden voyage from Southampton to New York City. There were
an estimated 2,224 passengers and crew aboard, and more than 1,500 died, making it one of the deadliest
commercial peacetime maritime disasters in modern history. RMS Titanic was the largest ship afloat at the time
it entered service and was the second of three Olympic-class ocean liners operated by the White Star Line. It was
built by the Harland and Wolff shipyard in Belfast. Thomas Andrews, her architect, died in the disaster.
Dataset:
The Titanic dataset can be downloaded from the Kaggle website which provides separate train and test data.
The train data consists of 891 entries and the test data 418 entries. It has a total of 12 features.
Exploratory data analysis:
As in different data projects, we'll first start diving into the data and build up our first intuitions. In this section,
we

**_Dataset:_**
The Titanic dataset can be downloaded from the Kaggle website which provides separate train and test data.
The train data consists of 891 entries and the test data 418 entries. It has a total of 12 features.
Exploratory data analysis:
As in different data projects, we'll first start diving into the data and build up our first intuitions. In this section,
we'll be doing four things.
Data extraction: We'll load the dataset and have a first look at it.
Cleaning: We'll fill in missing values.
Plotting: We'll create some interesting charts that'll (hopefully) spot correlations and hidden insights out of the
data

**CSV FILES IMPORTED FROM KAGGLE**

[test.csv](https://www.kaggle.com/c/titanic/data?select=test.csv)

[train.csv](https://www.kaggle.com/c/titanic/data?select=train.csv)

[gender_submission.csv](https://www.kaggle.com/c/titanic/data?select=gender_submission.csv)

**DATA ANALYSIS BY PLOTTING**

**ANALYSIS**

- **_Checking Age of All Passengers_**
![Screenshot (363)](https://user-images.githubusercontent.com/44723903/90952851-76e8b680-e484-11ea-9ef6-3f6b95e7eb54.png)

- **_Pclass varies in terms of age distribution of passengers, class3, most did not survive wheres infants in 2 and 3 survived and mostly all in 1 survived_**
![Screenshot (364)](https://user-images.githubusercontent.com/44723903/90952894-c4fdba00-e484-11ea-8f50-3d99589c4d14.png)

- **_Hence, females had much better survival rate and added sex feature to model alongwith embarked port feature.
too_**
![Screenshot (365)](https://user-images.githubusercontent.com/44723903/90952909-efe80e00-e484-11ea-90e3-9cde94375691.png)

- **Hence, high paying passengers survived more, and thus we consider banding fare feature in our model**
![Screenshot (366)](https://user-images.githubusercontent.com/44723903/90952925-09895580-e485-11ea-992c-880e7d111319.png)

**MODELLING:**

In this part, we use our knowledge of the passengers based on the features we
created and then build a statistical model. You can think of this model as a box
that crunches the information of any new passenger and decides whether or not
he survives. A variety of ML algorithms were used and models created for **SVM,
KNN, Logistic Regression etc.**, Steps:

- Break the combined dataset in train set and test set.
- Use the train set to build a predictive model.
- Evaluate the model using the train set.
- Test the model using the test set and generate and output file and import it
to another csv file

Compare the performance of various models and choose the **best fit**

**MODEL SCORE**

**BEST MODEL SCORE : 86.76 (Decision Tree)**

- **_In these case the best model score is for Decision Tree followed by KNN and Logistic Regression._**
![Screenshot (451)](https://user-images.githubusercontent.com/44723903/90953961-bbc51b00-e48d-11ea-99ab-704d802c6d5e.png)

**submission.csv FILE shows the list of people with passenger id that have
survived.**

