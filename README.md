
# A Gentle Introduction to Machine Learning

https://www.youtube.com/watch?v=Gv9_4yMHFhI

- Fitting the Training Data well but making poor predictions, is called the Overfitting
- Machine Learing is all about making Predictions and Classifictions
- Overfitting: Good performance on the training data, poor generliazation to other data. 
- Underfitting: Poor performance on the training data and poor generalization to other data.

![image](https://user-images.githubusercontent.com/60442877/149464318-d2f82b92-1b4a-4df1-91ee-c9f195db4879.png)



# Bias and Variance

https://www.youtube.com/watch?v=EuBBz3bI-aA&t=0s

- The model fits the training data really well, but not the testing set, we say that the model is overfitting
- There are three commonly used methods for solving overfitting problem is: 
- 1. Regularization
- 2. Boosting
- 3. Bagging
- In machine learing terminology, the difference in fits between testing and training data sets is called variance (or variation)
- The inability for a machine learing model to capture the true relationship in training dataset is called bias
- Note that, the bias and variance definition in Statistics is different from the one of Machine Learning

# Cross Validation

https://www.youtube.com/watch?v=fSytzGwwBVw&t=0s
 
- Cross Validation allows us to compare different machine learning methods and get a sense of how well they will work in practice
- n-fold cross valiation
- The extreme case, leave one out cross validation
- If we want to use a method that involves a 'tuning parameter', a parameter that isn't estimated, but just sort of guessed (for example, K-NN, the K value), then, we can use cross validation to help us find the best parameter value for that tuning parameter (Validation Dataset)

# Confusion Matrix

https://www.youtube.com/watch?v=Kdsp6soqA7o

![image](https://user-images.githubusercontent.com/60442877/149466730-196531f7-4d8a-4a41-b557-a8599ccc970a.png)

- True Positive: both the predicted label and the  label are positive
- True Negative: both the predicted label and the true label are negative
- False Positive: the predicted label by model is positive, however, the true label is negative
- False Negative: the predicted label is negative, however, the true label is positive

# Metrics： Sensitivity (Recall), Specificity and Precision

https://www.youtube.com/watch?v=vP06aMoz4v8

- Sensitivity or Recall (first column of confustion matrix): the percentage or proportion of true labels of positive that are correctly classified by model
![image](https://user-images.githubusercontent.com/60442877/149472743-3c695746-b05c-4c29-b993-03e752474f56.png)
![image](https://user-images.githubusercontent.com/60442877/149472819-6a216abc-d320-4dd9-93b2-24fd0ceb3068.png)
- Specificity (second column of confustion matrix): the percentage or proportion of true labels of negative that are correctly classified by model
![image](https://user-images.githubusercontent.com/60442877/149473181-965ae655-0a2a-41ce-a03f-17c198c5b98e.png)
![image](https://user-images.githubusercontent.com/60442877/149473116-6dd3b942-1535-4626-b5c4-0097a6fc3ed2.png)
- Precision (first row of confustion matrix): the percentage or proportion of predicted labels of positive that are actually true label
![image](https://user-images.githubusercontent.com/60442877/149480218-6ce80acb-2e2f-4b74-ae1e-c3a69dbd27e0.png)

Note: 
1. If correctly identifying positive labels is the most important thing to do with the data, we should choose a method with higher sensitivity
2. If correctly identifying negative labels is the most important thing to do with the data, we should choose a method with higher specificity





# Metrics: ROC and AUC

- ROC
- AUC

