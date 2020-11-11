# Linear-classifiers

## Dataset Info
This is a dataset that consists of various features of NASA confirmed planets. The pertinent ones are:
* Orbital Period [days]
* Planet Mass or M*sin(i) [Jupiter mass]

#### Source
Data was produced by the NASA Exoplanet Archive: http://exoplanetarchive.ipac.caltech.edu
* Confirmed planets --> https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=planets
* Downloaded the table as a CSV file --> My file name: planets_2020.09.03_20.35.38.csv
* BUT, for ease of filename usage, I renamed to: planets090320.csv

## Purpose
The purpose in studying this dataset is to classify and compare planetary systems, specifically with regards to their quantitative properties. Plotting these properties can provide insight on the interactions and correlations between them. We do this by training an Adaline model and logistic regression model to classify between Jupiter-mass planets (class J) and Earth-mass planets (class E) based on mass and orbital period.

We will compare the performance of the different models in their classification of these planets. This can be an important task because of the different properties, compositions, behaviors, etc. of different classes of planets. This has effects on their motion, aging, reactions (chemical, atmospheric, etc), interactions with space and bodies around them, etc. Our very understanding of the universe can be based on our studies of the different celestial bodies. 
