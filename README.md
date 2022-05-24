# LoanClassification

In this project I used Python to train Machine Learning Algorithms for classification purpose.
I used six algorithms in total, they are:

1. Logistic Regression
2. KNN
3. SVM
4. Naive Bayes
5. Random Forest 
6. SGD 

For the Model Evaluation, I used:
1. Mean Absolute Error
2. F1 Score
3. AUC
4. Accuracy
5. Confusion Matrix

This project was inspired from this two references, so go check them out:
1. [Loan Status Classification](https://www.kaggle.com/code/sazack/loan-status-classification)
2. [Top 6 Machine Learning Algorithms for Classification](https://towardsdatascience.com/top-machine-learning-algorithms-for-classification-2197870ff501)

![image](https://user-images.githubusercontent.com/103926829/170031285-5e6bb71c-a746-4d2b-8a2b-be25c4a5c595.png)

**What do you think of the result?** 

I'm gonna give you my two cents. based on the Mea, F1, and Accuracy the five algorithms other than Naive Bayes doing so well.
The five algorithms except Naive Bayes if you take a look on the confusion matrix is that they prone to predict towards the positive 
(The number are high in TP and FP). I would assume this because of the distributions of the Y variables which are dominated by the class of 1. 
And if you take a look of the SVM it just failed perfectly of predicting the class 0 and yet still get the higher accuracy and f1 score than NB.
This is why you can't depend only on certain metrics to evaluate models.
I'm sure there are still so much gap to fill and that would be my motivation to do better.
