# Boosting

Boosting in another method of creating a strong learner from various weak learners.
<br>
It is a sequential method in which the learners are created in a sequential manner and the errors/misclassifications from the previous model/learner
are given a higher weight to be included in sample that will be selected for training the next learner/model.<br>
This goes on till a condition is met such as batch size or the time reached.<br>
The result of all the learners is combined together(not averaged as it is done in Bagging) and the sum is considered the prediction.

![](https://i.postimg.cc/LXs4pCFN/SCR-20220909-unn.png)
