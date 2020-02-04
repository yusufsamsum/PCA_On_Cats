# PCA_On_Cats
Dimension Reduction with PCA
Dimension reduction on cat images with PCA. This repository includes Bilkent University Introduction to Machine Learning course assignment. The problem definition is given below:

In this question, you are expected to analyze cat images using PCA. You will use the dataset provided within the homework zip file as cats. The dataset is composed of 5000 images of cats. For this question, use of any library for PCA calculations is not allowed.
Flatten all images of size 64×64×3 to get 4096×3 matrix for each image. Note that all images are 3-channel RGB. Create a 3-D array, X, of size 5000 × 4096 × 3 by stacking flattened matrices of the images provided in the dataset. Slice X as Xi = X[:,:,i] where i corresponds to the first three index. thus obtaining each color channel matrix independently for all images. Reshape all Xi to obtain matrices, instead of 3D arrays.
