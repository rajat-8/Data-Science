# Disaster Response Web App

## Installation
The code contained in this repository was written in Python 3, and requires the following Python packages: json, pandas, nltk, sklearn, sqlalchemy, sys, numpy, re, pickle, warnings.

## Project Overview
This repository contains which an emergency worker could use during a disaster event (e.g. an earthquake or hurricane), to classify a disaster message into several categories, in order that the message can be directed to the appropriate aid agencies. This code could be tranformed into a web app usingb Flask.

## Introduction
This code is majorly divided into two , In the fisrt part we have extracted the data from the csv files and cleaned the data according to our 
requirement. Which included one-hot encoding the data with merging and removing the useless data.




## Warning
The datasets included in this repository are very unbalanced, with very few positive examples for several message categories. In some cases, the proportion of positive examples is less than 5%, or even less than 1%. In such cases, even though the classifier accuracy is very high (since it tends to predict that the message does not fall into these categories), the classifier recall (i.e. the proportion of positive examples that were correctly labelled) tends to be very low. As a result, care should be taken if relying on the results of this app for decision making purposes.

