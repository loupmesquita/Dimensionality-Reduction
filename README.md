# Dimensionality-Reduction
## Dimensionality reduction and visualization on meteorological data

A meteorological station has gathered 800 data samples in dimension 6, thanks
to 6 sensors. The operators of the station would like to predict the risk of a tempest
the next day, but first, they need to reduce the dimensionality of the data, in order
to apply a supervised learning algorithm on the reduced data.
The data are stored in : <br> <br>
— data.npy contains the raw data <br>
— labels.npy contains the results for each sample : 1 if there is a tempest, 0 otherwise. <br> <br>
The goal is to perform a dimensionality reduction of the data, to a dimension of 2 and 3 and
plot these reductions onto scatter plots in dimension 2 and 3 as well, coloring the
projected samples according to the label of the original sample. <br>
At the end we should understand according to the results which dimensionality reduction method fit the best to the data

## Disclaimer 

The 3d plots may not charge on github, to visualize them you need to open the notebook in an appropriate editor (Colab, vscode...)
