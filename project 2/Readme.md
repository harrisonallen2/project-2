Project 2 ( Credit Card fraud Detection )

![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.001.jpeg)

*Background:*

Credit Card Fraud Detection with Machine Learning is a process of data investigation by a Data Science team and the development of a model that will provide the best results in revealing and preventing fraudulent transactions.

In this assignment we have built the Credit Card Fraud Detection Machine Learning Model.

You will need to:

1. Get data from Kaggle.
1. Explore the data.
1. Preprocess the data.
1. Build a Ml model.


First we downloaded the credit card fraud detection data from Kaggle and loaded it with the Panda Library.

**Data Cleanup & Model Training:**

We checked the missing value for data cleanup, no missing value was found ther**e.**Then we describe the data to analyze the data well.Then I did a data column show.

After doing these we plotted the distribution with each of the target values of the data.


![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.002.png)



Then we counter-plotted Fraud & Note Fraud from Dataset

![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.003.png)

Plotting Distribution of ['Amount', 'Time'] Variables in T Datasets

![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.004.png)

Then we did data scaling. Scaling data is very important. Scaling the data increases the accuracy of the machine learning model. We have done robust scaling and standard scaling

After scaling, we split the data into x and y. X variable has no class columns and y variable has class columns.Then we investigate the correlation of our new subsample.

Imbalanced Correlation Matrix (Original Dataset with Scaled Features Time and Amount.

![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.005.png)

Subsystem correlation matrix

![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.006.png)


Then we divided the dataset into 4 parts. And we used 20% for data testing

After processing the data, we finally built the machine learning model. We chose the logistic regression model.

Logistic regression gave us 94% accuracy. Which is a lot better.


Then we find out the Confusion Matrix of Logistic Regression


![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.007.png)

Finally we released the classification report

![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.008.png)


- Which model will give more accuracy for credit card fraud detection?
- Ans: Logistic Regression .



- Can I get higher scores if I use gridSearchCV in logistics regression?
- Ans: Logistics regression validation score will be 93%


- How to find Percentage of normal transactions and Percentage of fraud transactions and Total number of transactions in resampled data?

- Ans: ![](Aspose.Words.23cf85e1-0be7-4dd5-b513-c31fcd29a1da.009.png)


