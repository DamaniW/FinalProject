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

### Machine Learning Models

Since this is a simple Classification problem, because we are only looking at one target variable with a value of 0 or 1, I decided to use all the classificatoin models taught in the course (in my previous ML project, I did not use enough models). Then in the end I will use the accuracy scores and compare them to see if there is a consensous between the models or if one is much better than the other. 

Balanced Random Forest (main)

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/BRFreport.png?raw=true)

Easy Ensemble Classifier

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/EECreport.png?raw=true)

Logistic Regression

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/LRreport.png?raw=true)

Naive Random Oversampling

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/NROreport.png?raw=true)

SMOTEENN Oversampling

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/SMOTEENNreport.png?raw=true)

### Conclusion

Based on the accuracy reports of the different models, it is safe to say that YES, it is possible for hotels to predict if a person will cancel. 
HOWEVER, I did not take into account certain variables that would have outliers or features that could vary multiple ways. Therefore, the accuracy of the models was a little too high for my liking. The professor always told us, "If it looks too good to be true, then it isn't". But, I still stand by my findings and with a little tweaking can produce a much more accurate model.

![alt text](https://github.com/DamaniW/FinalProject/blob/main/Images/accuracy_scores.png?raw=true)
