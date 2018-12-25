.. _introduction:

Introduction
============

What is Machine Learning?
-------------------------
Machine Learning is the science of getting computers to learn, without being explicitly programmed.

A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.

Example: Playing Checkers.

E = the experience of playing many games of checkers

T = the task of playing checkers.

P = the probability that the program will win the next game.

Machine Learning Algorithms

- Supervised Learning
- Unsupervised Learning

Feature - A feature is a measurable property of the object you're trying to analyze

Label - The output you get from your model after training it

Supervised Learning
-------------------
In Supervised Learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.

Supervised Learning is categorized into

- Regression (continuous output)
- Classification (discrete output)

In a regression problem, we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. In a classification problem, we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.

Example:

(a) Regression - Given a picture of a person, we have to predict their age on the basis of the given picture

(b) Classification - Given a patient with a tumor, we have to predict whether the tumor is malignant or benign.

Unsupervised Learning
---------------------
Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.

We can derive this structure by clustering the data based on relationships among the variables in the data.

With unsupervised learning there is no feedback based on the prediction results.

Example:

Clustering: Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.

Non-clustering: The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a cocktail party).