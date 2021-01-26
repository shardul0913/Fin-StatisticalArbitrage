# Fin-StatisticalArbitrage

The financial model is a implementation of techniques shown in the fantastic paper 'Machine Learning in Asset Management' by Derek Snow.

Time series modelling using GMM (Gaussian Mixture Modelling) and Expectation Maximization.

#Problem Statement : 

1. Understanding the stationarity of the returns
2. Understanding the behaviour of returns over a period of time while understanding the fundamental differences in the distributions for the test and train splits before GMM implementation. 
3. Selecting the observations with maximum likelihood to be from the same distribution
4. applying the GMM for the distribution clusters in the pobability space
5. Applying EM to tune the problabilty parameters and to get the future predictions based on the current distribution of the training values 

The unsupervised method to understand the historical prices and calculating the returns based on the past behaviour comes under 'Priced based trading strategy'

As part of improvement this implementations will also be focusing on the supervised approach to the GMM clustering add solution around the same
