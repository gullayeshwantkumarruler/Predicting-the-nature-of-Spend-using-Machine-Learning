# Predicting-the-nature-of-Spend-using-Machine-Learning
Predicting the Spend category of an individual using Machine Learning

Fresco Problem Analysis 
- Fresco market being one of the biggest business markets in the UK wishes to identify trends and patterns in a sample of weekly data collected for a number of their loyalty cardholders during a 26-week period. The data includes information on the customers’ gender, age, shopping frequency per week and shopping basket price. Fresco operates two different types of stores (convenience stores and superstores) but they also sell to customers via an online shopping platform. The collected data are from all three different types of stores. Finally, the data provide information on the consistency of the customer’s shopping basket regarding the type of products purchased. These can vary from value products to brands as well as the supermarket’s own high-quality product series Fresco Top. 
- Now The Fresco marketing management team is only interested in identifying whether the spending of the potential customer will fall into one of three possible groups including:
 - Low spender (shopping basket value of £25 or less)
 - Medium spender (shopping basket value between £25.01 and £70) and
 - High spenders (shopping basket greater than £70) 


- We have the data of about 75 rows and 8 columns which is considerably less but the good thing to note is that there are no null values in the data. The shopping basket value is given in float so as we want to categorize the values in three categories, we have used binning to bin the values.
- We have even observed that there is high correlation between columns so using only logistic regression might not help so we have even used a tree based method like decision tree and tuned the same on the data.
- We started with logistic regression and further dwelled into decision trees and also performed pre-pruning and post pruning in decision trees to check for their performance.
- We observed that the post-pruned decision tree gave the best performance.
- We can observe that the decision tree post pruning has an overall accuracy, precision, recall and f1-score around 75%.

