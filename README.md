# BSAN-6070
CA02
In this exercise, I built a model with a set of emails marked as coming from spam or not spam. There are 702 emails divided equally into spam and non-spam categories. Next, we will test the model on 260 emails. We will ask the model to predict the category of this email and compare the accuracy to what we already know is the correct category.
I first import necessary packages as the prepartion of the model. 
Then I count the word frequency of the document and then removed the less common word for the document. 
I extracted the 3000 most frequently used words in the end.
Then I generated a label and word frequency matrix.
Finally, I used the model with the two data files, Train_Mails and Test_Mails.
I used Gaussian method to compare the accuracy score for predicted labels. Accuracy score is just percentage of correct predictions.
0.9653846153846154 -- here is the result.
