## Tackling powerline fault location with supervised machine learning
## [Link to the dataset](https://www.kaggle.com/datasets/esathyaprakash/electrical-fault-detection-and-classification)

## [Link to final report](https://docs.google.com/document/d/1mjoQEIyxzc1QiHSIAmltiGrD6pOn2O9eqoP4XNtfSpE/edit?usp=sharing)

## Problem description
The main objective of the analysis here is to focus on prediction. We want to build a model that will determine if a line is faulted and what type of fault it is to better deploy technicians with the right tools to enable minimum downtime.

This project directly benefits the business by creating tripwires for response generations immediately when a fault occurs instead of waiting for an outside report.
It also creates a more informed on-site technician. With knowledge of the fault type the technician is able to plan, gather appropriate tools and the required number of people. This tool also assists the plant managers. If a fault is observed, they can take immediate action on the distribution of power to ensure zero downtime for customers.

## Features of the data
The dataset has the following attributes:
- Four different feature columns to specify which phase is faulted and if the connection to ground is faulted 
- These are indicated by 0/1 values in various columns
- The Line Current for all three phases measured in ampere
- The Line Voltage for all three phases measured in volts


## Models used
- Logistic Regression
- KNN
- SVC

## Technologies used
- Jupyter Notebook
- Python
- Git