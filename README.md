# Handling-Imabalanced-dataset Using SMOTE

Hello,

The problem of imbalanced datasets is very common and it is bound to happen. This problem arises when one set of classes dominate over another set of classes. It causes the machine learning model to be more biased towards majority class. It causes poor classification of minority classes. Hence, this problem throw the question of “accuracy” out of question. This is a very common problem in machine learning where we have datasets with a disproportionate ratio of observations in each class.

Feeding imbalanced data to your classifier can make it biased in favor of the majority class, simply because it did not have enough data to learn about the minority.

Now, there are various approaches to deal with this problem.

In this repository we will look into over sampling approach on car Evaluation Dataset. In this, I will discuss one of the sampling techniques — Synthetic Minority Over-Sampling Technique, abbreviated as SMOTE.

SMOTE:Just like the name suggests, the technique generates synthetic data for the minority class.

The SMOTE algorithm works in 4 simple steps:
a. Choose a minority class input vector
b. Find its k nearest neighbors (k_neighbors is specified as an argument in the SMOTE() function)
c. Choose one of these neighbors and place a synthetic point anywhere on the line joining the point under consideration and its chosen neighbor
d. Repeat the steps until data is balanced

SMOTE is implemented in Python using the imblearn library.


