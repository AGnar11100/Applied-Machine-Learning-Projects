These are the projects I completed in Applied Machine Learning (CSE 144) @ UCSC by Narges Norouzi Summer 2020. 

All the projects I completed in Google Collab. 

1) Monte Carlo and Data Processing was a simple assignment that allowed for students to get 
their feet wet with Python and data visualization tools such as seaborn.

2) Binary Classification and Neural Netnets introduced the use of logistic regression in Binary Classification and how 
we are able to do various types of polynomial transformations to reach a decision boundary that seperates the two classes. The Neural Nets
half of this notebook is a simple implementation of a NN in tensorflow and keras. 

3) Multi-Class Image Classification explores the Fashion-MNIST dataset and CIFAR-10 dataset. The project starts with doing some processing
and transforming on the fashion dataset. I then create a simple NN that does a binary classification and works well. The next half
of the assignment (uses CIFAR-10), in my opinion, was designed to exploit the advantages of convolutional NN and for multi-image classification.

4) Time-Series Forecasting explores the United States Corona Virus dataset where I used LSTM Architecture to create a sequential model. 
The model is not too complex and this exercise was just to exhibit the concepts of LSTM. The B&W Image Denoiser is a autoencoder that has 
the ability to do exactly what it's name is. It can be seen that using a regular AE is not ideal and that a GAN or VAE would be seen
to be more robust with this type of data/problem.

5) Wisconsin Breast Cancer with Random Forest explores the Wisconsin Breast Cancer dataset for classification. This notebook shows how PCA's
can be used with the Random Forest ensemble method to improve the time it takes for predictions. My model was able to speedup predictions from a 
stand-alone Random Forest model to a PCA-RF model by about double which made sense since the feature space is consolidated from 30 to 14 dims. 
