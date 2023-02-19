# LogisticRegression-LDA-QDA-Classification #CodeDaniel
Using Logistic Regression, LDA and QDA on Mushroom Dataset (Classification)
This project is a classification model that uses three different algorithms, logistic regression, linear discriminant analysis (LDA) and quadratic discriminant analysis (QDA), to classify mushrooms as either poisonous or edible. The data used for this project was taken from Kaggle, and it consists of information on various attributes of different types of mushrooms.
The first step in the project was to import the necessary libraries, including pandas, numpy, and scikit-learn. After that, the mushroom data was loaded into a pandas dataframe and the class column was encoded using the LabelEncoder class from scikit-learn.
The next step was to split the data into training and testing sets using the train_test_split function from scikit-learn. The logistic regression, LDA, and QDA models were then trained on the training set and used to make predictions on the testing set. The predictions were then evaluated using the confusion matrix and the ROC curve.

The results show that all three models performed well. The ROC curve for each model showed that they all had good discriminatory power.

In conclusion, this project demonstrated the use of three different algorithms for classification, and showed that they are all effective at classifying mushrooms as poisonous or edible based on their attributes. The logistic regression model was found to be the most accurate, but all three models are useful for this task.

Special thanks to Marco Peixeiro for motivating & guiding me in the project. 
