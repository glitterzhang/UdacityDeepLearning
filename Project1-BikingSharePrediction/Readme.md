This project is to build a neural network from scratch to implement on a prediction problem-predict daily bike rental ridership.

            ----Files----

Bike-Sharing-Dataset: 
This files contains bike sharing data to feed models. You can find detailed explanation for data in Readme.txt under Bike-Sharing-Dataset file.
	- hour.csv : bike sharing counts aggregated on hourly basis. Records: 17379 hours
	- day.csv - bike sharing counts aggregated on daily basis. Records: 731 days
    
myanswers.py: 
This file is to build neural network object from scratch. It includes feed-forward and backprogation process.
The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is  f(x)=x.  You can adjust the number of hidden layers and activation function based on your need.

Neural_network_predict_bike_sharing.ipynb: 
This file is to implement neural network on bike sharing prediction project.

test.py:
This file is the unitest file.

           ----How to run----
           
Before you run this project, make sure you have already have python and Anaconda installed on your computer.You can find the installers and installation instructions for Anaconda at https://www.continuum.io/downloads.

Once you installed Anaconda,please install the required packages under conda environment. To install packages,type:
conda install package_name
    
e.g. conda install numpy scipy pandas jupyter notebook

Packages we need for this project:
numpy
pandas
jupyter
notebook
matplotlib


Once all require packages install in you environment, then type 
   jupyter notebook
under your command prompt. 

            ---- Materials-----
 
https://skymind.ai/wiki/neural-network

http://ruder.io/optimizing-gradient-descent/index.html#momentum
