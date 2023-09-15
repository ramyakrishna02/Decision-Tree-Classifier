# Decision Tree Classifier
A decision tree is a versatile supervised machine-learning algorithm, which is used for both classification and regression problems. It provides a clear indication of how a decision was made and can generate understandable rules. Decision trees are able to handle both continuous and categorical variables.

It is a flowchart-like tree structure used in machine learning.It is constructed by recursively splitting the training data into subsets based on the values of the attributes until a stopping criterion is met, such as the maximum depth of the tree or the minimum number of samples required to split a node.

During training, the Decision Tree algorithm selects the best attribute to split the data based on a metric such as entropy or Gini impurity, which measures the level of impurity or randomness in the subsets. The goal is to find the attribute that maximizes the information gain or the reduction in impurity after the split. 

## Implementation
- Importing the required Libraries and reading the dataset
- Performing EDA (Exploratory Data Analysis) on the data
- Encoding the Categorical Variables
- Normalization of the data
- Splitting the data into the Train and the Test data
- Building the Model
  -  Decision Tree Classifier model using Entropy Criteria (C5.0)
  -  Decision Tree Classifier model using Gini Criteria (CART)
- Conclusion

## Packages Used
- pandas
- numpy
- seaborn 
- matplotlib.pyplot
- warnings
- from sklearn import preprocessing
- from sklearn.model_selection import train_test_split
- from sklearn import tree
- from sklearn.tree import DecisionTreeClassifier
- from sklearn.metrics import classification_report
