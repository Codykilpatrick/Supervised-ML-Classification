## Tackling powerline fault location with supervised machine learning
## [Link to the dataset](https://www.kaggle.com/datasets/esathyaprakash/electrical-fault-detection-and-classification)

## [Link to final report](https://docs.google.com/document/d/1mjoQEIyxzc1QiHSIAmltiGrD6pOn2O9eqoP4XNtfSpE/edit?usp=sharing)


The main objective of the analysis here is to focus on prediction. We want to build a model that will determine if a line is faulted and what type of fault it is to better deploy technicians with the right tools to enable minimum downtime.
This project directly benefits the business by creating tripwires for response generations immediately when a fault occurs instead of waiting for an outside report.
It also creates a more informed on-site technician. With knowledge of the fault type the technician is able to plan, gather appropriate tools and the required number of people. This is different from the current method of, show up to site, evaluate, plan, return to shop and gather tools, then return to site to fix the fault.
This tool also assists the plant managers. If a fault is observed, they can take immediate action on the distribution of power to ensure zero downtime for customers.


The data set I chose was Electrical Fault detection and classification from Kaggle. It measures power lines voltage and current then displays if that line is faulted and if it is what kind of fault it is.
The dataset has the following attributes:
● Four different feature columns to specify the exact fault
○ Between Phase A and Ground
○ Between Phases A,B and Ground
○ Between all three phases
○ And more similar variations
○ These are indicated by 0/1 values in various columns
● The Line Current for all three phases
○ Measured in ampere
● The Line Voltage for all three phases ○ Measured in volts
I am trying to use the Line Current and Line Voltage to predict the fault category column. I believe that there will be some if not a large variation in the current/voltage between the faulted and non faulted lines.

Models used:
Logistic Regression
KNN
SVC