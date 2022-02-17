# “Are They Going to Cancel?” Hotel Analysis
## Damani Walker


### Overview

When planning a trip, we all dread the moment when one of our friends makes a
last minute cancellation.
What about from the perspective of the hotels?
Can they predict when a person or party is going to cancel based on different
variables?

In this project, I will be using Machine Learning models to predict wheather or not hotels can predict if a booking will be cancelled ahead of time.

### Data Preparation

The dataset is a csv gathered from kaggle.com, which is a data science community,that provide different datasets for various industries or businesses.
The dataset provided over 100,000 rows and 32 columns of features to utilize (one of my issues when working with machine
learning). Additionally, the data needed to be cleaned of nulls, duplicates and converted into numerical values for catagories that needed it.

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/raw_data.PNG?raw=true)

### Data Analysis

The variable I chose as my target was the “is_canceled”

Then, I wanted to see how the other variables correlated with the target variable.

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/CorrelationMap.PNG?raw=true)

From this, I was able to point out the most important variables that would affect the target.

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/important_features.png?raw=true)
