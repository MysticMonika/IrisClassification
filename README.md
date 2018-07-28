# IrisClassification
 classification using iris dataset

 # Data Set #
 [link to data set](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data)

 Iris dataset is perhaps the best known database to be found in the pattern recognition.
 It has 3 classes that are Iris-setosa, Iris-verticolor, Iris-virginica.
 The data set contains 3 classes of 50 instances each.

 # Procedure #
 To know the data well we tried to built different kinds of graphs. After that perform training and testing over iris data collectively. There we get to know about  accuracies  over different models
 Then we will use 1 Petal Feature and 1 Sepal Feature to check the accuracy of the algorithm as we are using only 2 features that are not correlated. Thus we can have a variance in the dataset which may help in better accuracy.

 # Accuracy Table #
## Overall accuracy of dataset over different model ##

    |  SVM    | DecisionTree |   KNN   | LogisticR
----|---------|--------------|---------|------------    
acc | 0.98095 | 0.97142      | 0.97142 | 0.96190


## Accuracy of Petal and Sepal seperatly ##


              |    SVM   |  DecisionTree |  KNN   |  LogisticR
    ----------|----------|---------------|--------|-------------          
    Petal Acc.|  0.97    |  0.95         |  0.97  |  0.68
    Sepal Acc.|  0.8     |  0.42         |  0.75  |  0.64
