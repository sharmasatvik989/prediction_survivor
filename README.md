# prediction_survivor

Project is based on predicting the survival of passenger on the titanic dataset classifying how many passengers survived based on their class, sex and age.

For the project I have used random forest classifier as per the dataset suing decision tree is an ideal choice and that is what is what I have done.

The data required some preprocessing such as:
1.	Removal or replacing of Nan values from the dataset 
2.	Classifying the “Age” column of the dataset into three categories of Young, middle and old with value 1,2 and 3 respectively.
3.	The percentage of every survived passenger in the training dataset based on the features pclass, age and sex has also been defined.

Now the data preprocessing after classifying the age column I have shown with graphs that young first-class women passengers are the most one who survived.
The random forest classifier has used 4 features for the prediction on the test data which are
Pclass , Age, Sex and SibSp to achieve the accuracy of 83%.
