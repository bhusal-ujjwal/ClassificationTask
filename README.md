# ClassificationTask
The dataset description:
These datasets can be viewed as classification or regression tasks for wine dataset
The classes are ordered and not balanced (e.g. there is much more normal wines than excellent or poor ones). 

Attribute Information:
For more information, read [Cortez et al., 2009].
Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol


Output variable (based on sensory data):
12 - Type

You must read the data using Pandas library and first read the first 10 rows using the head function
you must describe the data using the relevant functions.
Create a correlation matrix out of the data, and the using seaborn library to visualize the data
if the data is not shown correctly and everything is too messy, try to change the size of the heat map using matplotlib library by changing rcParams.
using Sklearn library split the data into train and set set with the ration of 25% for test and 75% for training.
Classify the data once using LogisticRegression and once with KNeighborsClassifier
create a confusion matrix and classification report for both classifiers.
You must classify the type or the wine either it is red or white wine based on the attributes 
