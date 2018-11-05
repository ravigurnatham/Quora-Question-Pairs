# Quora-Question-Pairs
**Quora Question Pairs** problem is to find whether the given question pair duplicate or not.In each month Over 100 million people visit the Quora, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question.The task of machine learning model is to classify whether question pairs are duplicates or not. 

# Dataset 

##### Data fields

**id** - the id of a training set question pair

**qid1, qid2**- unique ids of each question (only available in train.csv)

**question1, question2** - the full text of each question

**is_duplicate** - the target variable, set to 1 if question1 and question2 have essentially the same meaning, and 0 otherwise.


# Objective and Constraints

1. Probability of the class required so that we can set a thresold value, such that based on the probability we assign data point to one of the class

2. performance measure is log-loss because log-loss rewards correct decisions and penalizes incorrect decisions.

