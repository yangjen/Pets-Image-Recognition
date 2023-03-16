# Cats_vs_Dogs
Kaggle Challenge

Introduction
The goal of this project is to distinguish Dog pictures from Cat pictures. This is an image recognization problem which was previously challenging for computer. However with the advance development of computer vision technique in machine learning. we are able to get much higher accuracy in such task. 

In this exercise, I compared the performance between traditional shallow CNN network and VGG16 pretrain model. To help with the model learning, I also added image augmentation step. 

Results: 
VGG16 is a deeper network thus it has a a better perfomance 0.88 comparing to 0.64 by CNN. To increase training speed I used a small batch size 32. Training with more epochs also helps with improving accuracy. Since the dataset is well balanced, I used a 0.5 threshold to get the final prediction from the model predicted probabilities. Finaly I used 5 folds cross validation on VGG16 to finalize on the 0.9 result. In the test set (without official labels), out of the 16 sample, we observe only 1 classified incorrectly.  
