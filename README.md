# EcoSync-Waste-Image-Classifier-and-Water-Quality-Analysis
This project aims to develop a comprehensive web-based platform that leverages modern technology to address two critical environmental challenges:  WATER AND WASTE MANAGEMENT. The solution integrates machine learning to promote sustainable practices and environmental consciousness by using various classifiers to obtain desired results which include classification of waste images and potability of water. 
# Overview:
+ There are LIGHT BLUBS, PAPER, PLASTIC, ORGANIC, GLASS, BATTERIES, CLOTHES, METAL, E-WASTE total 9 different types of waste materials which divided into their respective classes.
+ There are 450 images belonging 9 classes.
+ The classification on waste dataset has been performed by using 4 classifiers, namely: Decision Tree, Random Forest, XG Boost and Logistic Regression.
+ Dataset has been trained using VGG16 Transfer Learning technique of CNN for classification.
+ Here, the model has been trained using MLP Classifier and Adam Optimizer over 15 epochs and 81.267% accuracy was obtained.
+ The water potability analysis model has been created by training the csv dataset with 2 classifiers, namely: KNN and Logistic Regression.
+ After training using KNN and Logistic Regression, the accuracy of the model was 65.34% and 62.84% respectively.
# How to use:
+ The path of the image from the dataset needs to be copied and pasted in the code.
+ The image will be classified to it's respective class with accuracy.
# Technologies used: 
+ matplotlib
+ TensorFlow
+ NumPy
+ Pandas
+ Keras
+ scikit
