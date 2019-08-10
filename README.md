# PCA vs t-SNE
It has the comparison study on dimension reduction techniques PCA and t-SNE.
The dataset used here is MNIST train data set. It is openly available on kaggle. The dataset is that of character recognisation. 
we wish to try PCA and t-SNE and check which perform better. We bring down the dimension from 784 to 2D, so that we can easily visualise and contemplate better.

##PCA 
Principal component analysis is the most famous dimension reduction technique. It works on the principle of entropy preservation. In simples words, it is such a transformation that tries to explain the varience of data. The more the variance preserved, more the information. 

##t-SNE
t-Distributed Stochastic Neighbor Embedding is probablistic model. As the name suggests it works on the neighbourhood embedding. The process tries to find such an embedding(mapping) that it preserves the neighbourhood. If a point had 5 more points in the neighbourhood. t-SNE tries to map all the 6 points together in the transformation. It preserves the neighbourhood and dosent care outside it. This is local structure preserving dimensional reduction technique.
