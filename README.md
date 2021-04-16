# Explore and Analyse Seattle AirBnB Data
This repository contains files including the listings, property availablity, and reviews data for AirBnB properties listed in the Seattle, Washingtion area over the year 2016, as well as Python scripts in the form of a Jupyter Notebook which explores and analyse the data for a number of interesting questions that could be used to help potential hosts and renters who may use the AirBnB platform.

A companion blog post for this analysis can be found at https://chinnaporn-chinotaikul.medium.com/the-best-airbnb-locations-in-seattle-2be45c4d3809

Created as part of my project for the Udacity Data Science Nanodegree course

# Installation
The Jupyter Notebook was created using version 6.1.5 of the server and using Python version 3.8.5
Other libraries include:
- pandas (1.1.5)
- numpy (1.19.2)
- matplotlib (3.3.2)
- seaborn (0.11.0)
- scikit-learn (0.23.2)
- statsmodels (0.12.1)
- jupyterthemes (0.20.0)

# Project Motivation
The project aims to provide useful information and methods which could be used for analysing future data, for potential or current property owners or renters in the Seattle area who may be interested in utilisting the AirBnB platform

# File Descriptions
Files in this repository include:
- seattle-airbnb-exploration-analysis.ipynb - the main Jupyter Notebook includes importing of the data, exploration, analysis and visualisation

The below files had been uploaded in rar files due to size. Please unpack before use:
- calendar.csv - properties availability and pricing data throughout the period
- listings.csv - data of each listing including properites of the host as well as of the properties
- reviews.csv - all text reviews made on the properties

# Project Summary
For the project, I posed the following business questions:
<ol>
    <li>Which locations have the most expensive properties or the least expensive properties?</li>
    <li>Which locations have the highest rated properties?</li>
    <li>Do prices vary seasonally? In which periods are the prices highest or lowest?</li>
    <li>Can we predict the price of a property by its characteristics, and which characteristics have the highest correlation with price?</li>
    <li>Can we predict the average user rating of a property by its characteristics, and which characteristics have the highest correlation with rating?</li>
</ol>
In the course of the exploration and analysis, I found that different locations do have different average pricing and ratings. Prices do vary seasonally as well as over different days of the weeks, being apparently influenced mostly by weekends and holiday periods. I found that a reasonable model could be made to predict the pricing of a property, but not for the rating, although there are certain factors that appear to significantly affect a property's rating.

# Acknowledgement and Licensing
- AirBnB data gathered and provided by http://insideairbnb.com/
- Libraries' documentations
- Udacity course materials
- All files in this depository are free to use
