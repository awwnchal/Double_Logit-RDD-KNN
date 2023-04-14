# Double_Logit, RDD, KNN

Introduction

In this project, we will use the hotel_cancellation.csv dataset to estimate the treatment effects of assigning a different room to a guest on the likelihood of the room being canceled. We will use all other columns in the dataset as covariates.

Treatment Effects

We will first estimate the treatment effects using a simple linear regression model with the treatment indicator of a "different room is assigned" and all other columns as covariates. We will interpret the effect of the treatment indicator on the likelihood of the room being canceled.

# Double Logistic Regression

Next, we will use double logistic regression to measure the effect of assigning a different room on the likelihood of the room being canceled.

Bootstrap

We will then use bootstrap to estimate the standard error of the treatment effects measured in the double logistic regression model.

Observations
We will provide our observations for the results obtained from the above models.

# Regression Discontinuity Design (RDD)

Introduction
In this project, we will use the drinking.csv dataset to explore the effect of drinking on the likelihood of death by accident, suicide, and/or other causes. We will use the RDD to determine whether alcohol increases the chances of death.

RDD
We will perform the RDD by using a simple code to calculate the average to one side of the threshold (21 years old) minus the average to the other side. We will then plot graphs to show the discontinuity (if any) and to show results for the change in chances of death with all three features.

Legal Age for Drinking
Based on the results obtained, we will comment on the question of whether the legal age for drinking should be reduced from 21.

# k-Nearest Neighbors (kNN)

Introduction
In this project, we will use the iris.csv dataset to explore the performance of k-nearest neighbors algorithm in classification problems.

Performance of kNN
We will vary the value of k (1, 3, 5, 7) and observe how the performance of the kNN algorithm changes. We will choose an appropriate distance/similarity metric for the dataset and explain our choice. Finally, we will determine the optimal value of k.
