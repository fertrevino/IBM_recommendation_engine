# IBM_recommendation_engine
This repo contains the code for the IBM recommendation engine project for the Udacity Datascience Nanodegree.

## Introduction
The goal of this project is to create a recommendation engine for articles that might be interesing to users of the IBM Watson platform. The recommendation system has been built from an analysis of the interactions between users and articles.

## Description
The system can perform a recommendation whith the following different methods:

### Rank based recommendation
This type of recommendation gives the users a list of customized length with the highest ranked articles in the platform.

### Collaborative filtering
For this type of recomendation, we get the articles from users that are ranked as most similar to the user for which we want to provide a recommendation. The articles provided are those with recorded interactions with the similar users.

### SVD Matrix factorization
In this approach, we perform SVD to the interactinos matrix in order to study the accuracy of the prediction as a funciton of the latent features.


## Conclusion
This project has been useful in showing how a recommendation system can be constructed. It provided an insight on what type of variables one must look for as well as which type of operations are needed in order to complete the task. It has also been observed that the provided data set is limited and we may only test predictions in a reduced number of users, in this case 20. 

