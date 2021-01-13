# matplotlib-challenge
Analysis of Pymaceuticals' Capomulin drug (Rat Study)

# Overview
The purpose of this projecct was to create visual aids from Pymaceuticals's most recent animal study regarding possible treatments for squamous cell carinoma (SCC). Capomulin, a potential drug to combat SCC, has been in the Pymaceutical spotlight recently, so I was tasked with creating tables and visualizations of the data collected from the study. 

# Data cleaning
The data was reviewed for errors, incomplete datapoints, and duplicates. Duplicates were found and one mouse's data was deleted from the dataset. 

# Data Analysis & Visualization
Summary Statistics
Mean	Median	Variance	Standard Deviation	Standard Error (SEM) of each drug regimen group.

# Bar and Pie Charts
total measurements taken of each drug group
distribution of males and females

# Quartiles, Outliers, and Boxplots
final tumor volume from 4 of the top drug groups

# Line and Scatter Plots
randomly selects a mouse from the Capomulin group and puts it's tumor volume and timepoints in a line plot
scatter plot of the average tumor volume vs mouse weight for the Capomulin group

# Correlation and Regression
Linear regression modeling was used to determine any correlations between mouse weights and average tumor volume

# Reflections on Data:
1. Capomulin and Ramicane appear to have the most promising results. The data shows the average final tumor volumes were not only smaller when compared to the other drug regimens, but the tumor volumes had less variation and a lower standard error value (meaning the results are more reliable when making future predictions).
2. With that said, Capomulin and Ramicane were also the two drug regimens with the highest number of measurements, making them more reliable solely based on the fact that they had more data. Therefore, this could lead to unintended bias in favor of these two drug regimens. Further analysis on other drug regimens should be conducted to help account for bias.
3. When looking at the Capomulin group, there is a slight positive correlation with average tumor volume and mouse weights. Further analysis of average tumor volumes versus mouse weights should be conducted on the other drug groups to see if this correlation is consistent among all experiment groups.
