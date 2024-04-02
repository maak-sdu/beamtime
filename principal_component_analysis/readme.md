# Denoising using principal component analysis (PCA)

This iPython notebook will conduct PCA to denoise data. Denoising experimental  
data may improve visulization, when signal-to-noise ratio is low.

The data are expected to contain $x$-values in the first column and the  
$y$-values in the second column. Header as well as additional columns can be  
handled.

The data files should be names alphanumerically to be loaded in the right order.

The explained variance ratio (evr) can be used to set the level of the filtering  
for the denoising.

A plot of the explained variance ratio as functions of the number of components  
used during the PCA will be saved together with overview plots of the data,  
the pca-reconstructed (denoised) data, and the difference between the two.
