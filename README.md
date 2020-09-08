Car-Purchasing-Amount-Prediction

This predicts the car purchasing amount by a customer if certain features such as salary,credit card debt, networth ,age are provided.This model prediction is based on artificial neural network.
This dataset contains 500 rows and 9 columns.
By using sns.pariplot we found that only 5 columns are necessary to interpret further predictions.
Dependent variables which is the car purchasing amount and independent variables such as age,gender,networth,annual salary,credit card debt are defined. 
Independent variables are feature scaled using MinMax Scaler and the values ranges from 0 to 1.
The dataset is splitted into training set and test test.
Training set contains 375 rows and 5 columns.
Test set contains 125 rows and 5 columns.
Artificial neural network is used to train the model using Sequential method.
The model is trained for 100 epochs to minimise the rootmeansquare error which got reduced from 0.0104 to 0.0054 and loss got reduced from 3.51*e^-4 to 1.89*e^-5
The model gives the prediction of car purchasing amount by taking the values of independent variables in an array.
