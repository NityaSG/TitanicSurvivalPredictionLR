# TitanicSurvivalPredictionLR
 Kaggle competition(Logistic regression)

 Data :
Two .CSV file ; one for training the model and another for validation for submission

The data contains Various attributes with many of them not useful for the model training, for example Name and Embarked(Port of boarding on the ship)
Such attributes are not imported.

'PassengerId','Survived','Pclass','Sex','Age','SibSp' are the attributes to be used for model training.


Sex: model cannot interpret strings (male/female) hence here I have assigned values of -1 and 1 to Male and Female respectively (Note: didnt use the traditional binary(1 & 0) because in the case of 0, the weights would be cancelled)
