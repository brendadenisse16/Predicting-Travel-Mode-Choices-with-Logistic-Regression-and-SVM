# MachineLearning
Project: “Predict Travel Mode Choices: A comparison of the performance of machine learning classifiers”

This project will present three machine learning methods, namely multinomial logistic regression, multiclass Classification with Support Vector Machines, and random forest, to predict individuals' travel mode in The Netherlands. This study is useful for transportation planning based on travel behaviour, allowing us to predict individual preferences using a variety of transportation services.
Such a model is important, for instance, in planning new transportation projects or understanding human behaviour.


The presented methods will use individuals’ characteristics, transport mode specifications and data related to places of work and residence. The dataset analyzed comes from a survey of The Netherlands Mobility Panel (MPN) studies trends in the travel behaviour of a fixed group of individuals and households over a long. It contains information on the daily mobility (e.g., from home to work) of individuals who either live or work in The Netherlands. 
We will extract the survey's related daily movements (journeys between home and work, in particular) to the characteristics of working individuals. Given the amount of data, we will use only the travellers from North Holland of the Netherlands. 
A total of 7,310 observations (N trips) collected from 676 individuals (G individuals) will keep for our analysis. 


The project relies mainly on sklearn and pandas. 

It contains the following files: 

./code/environment.yaml 	<-- conda environment for our project
./code/util/*.py 		<-- some utility functions we wrote 
./code/preprocessing/*.py 	<-- functions for preprocessing data
./code/training/*.py 		<-- functions for training data and plotting as well
./code/G03-Project.ipynb 	<-- notebook calling all main operations and showing report and tables
./code/data/mobility_dataset.csv <-- raw data set
./code/data/catalogue.csv 	<-- data set with labels defined for the variables used

* The only file to run is : G03-Project.ipynb which is going to call all internal dependencies previously mentionned.
* GPU is not required. 
* Training takes ~1 hour. 
* The G03-Project.ipynb notebook creates an images/report_images directory and saves report image results there.
* The mobility dataset was downloaded from https://www.mpndata.nl/



