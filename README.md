# beyesian-gmm-clustering
Bayesian Gaussian Mixture Model Clustering of the Iris dataset

The Iris dataset contains 3 groups of flowers, with 4 features desribing each flower.

first let's look at the data (4d data so 1d is removed using PCA):

<img src="https://raw.githubusercontent.com/y0natancohen/bayesian-gmm-clustering/main/photos/data.png" width="700" height="150">

My model, reduces the dimension 4d -> 1d and performs bayesian gmm on the 1d data.

This gives as a 95% accuracy clustering function.

by giving a gaussian over the weights, centered at the PCA 1st component, the model simulates the data nicely, as shown in the folowing p-valuse diagram:

<img src="https://raw.githubusercontent.com/y0natancohen/bayesian-gmm-clustering/main/photos/p-values.png" width="700" height="250">
