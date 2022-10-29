## Introduction

This is a portion of a class project that I completed with 2 other students through the University of Michigan's Master of Applied Data Science program in Fall 2022. The course emphasized the development and evaluation of supervised and unsupervised learning methods.  This repo contains my work using python notebooks along with a pdf of our complete final report.

## Project Details
We used and participated in the course's Kaggle competition which provided over 400,000 sentences extracted from standard and simplified Wikipedia following the guidelines with a split training (containing labels) and a test set (unlabeled) for submission, both of which formed the basis for our dataset.  Our three-person team spent 4 weeks on the project completing the following:

 - Creating a data cleaning and processing pipeline for a final dataset leveraging 3 other auxillary resources assisting with evaluating word difficulty (as defined by what age/grade a person typically learns a particular word) , concreteness of meaning and other resources.
 - Perform Exploratory Data Analysis
 - Develop, train and evaluate 7 different classification algorithms using the best parameters found. Our seven classifier were:
    - decision trees
    - logistic regression
    - linear support vector machines
    - naive-bayes (multinomial variant)
    - random forest
    - XGBoost 
    - a dummy classifier (to keep us honest)
  
 - Evaluate the best classifier among the 7 and perform sensitivity, feature importance, feature ablation and error/failure analysis. Spoiler: We found the linear support vector machine was the best performer by a smidge over the naive-bayes classifer.
 
 - Explore different Unsupervised techniques (I evaluated the use of various clustering techniques while my teammate evaluated based on topic modeling) exploring different methods for tuning and evaluating results. My notebook entitled "dave-Sentence-Embedding-Clustering" covers working with several techniques including K-Means, the impact of clustering on PCA-transformed data, some exploratory work with Agglomerative and DBSCAN which I decided to create separate workbooks for further evaluation, and a couple other areas of supervised learning I didn't have much time to explore (t-SNE and MDS) given the abbreviated timeframe.

For my part, clustering wasn't as informative as I would've liked for it to have been, though Agglomerative Clustering exposed quite a bit about the nature of the data providing insight into how clusters formed.

