# matplotlib-challenge
Analysis of Pymaceuticals' Capomulin drug (Rat Study)

## Overview
The purpose of this projecct was to create visual aids from Pymaceuticals's most recent animal study regarding possible treatments for squamous cell carinoma (SCC). Capomulin, a potential drug to combat SCC, has been in the Pymaceutical spotlight recently, so I was tasked with creating tables and visualizations of the data collected from the study. 

## Data cleaning
The data was reviewed for errors, incomplete datapoints, and duplicates. Duplicates were found and one mouse's data was deleted from the dataset before continuing to the analysis. 

## Data Analysis & Visualization
Summary Statistics <p>
A summary statistics table was created to show the mean, median, variance, standard deviation, and standard error (SEM) of each drug regimen group.

## Bar and Pie Charts
A bar chart showing the total measurements taken of each drug group was created; Capomulin and Ramicane contained the most measurements. <p>
A pie chart showing the distribution of males and females in all groups combined was generated to check for even distrubution. 

## Quartiles, Outliers, and Boxplots
Boxplots were created to analyze the final tumor volume from the 4 top drug groups.

## Line and Scatter Plots
A script was created to randomly select a mouse from the Capomulin group and plot the corresponding tumor volumes and timepoints on a line plot<p>
A scatter plot of the average tumor volume vs mouse weight for the Capomulin group was created to analyze the data for correlations between weight and tumor volume. 

## Correlation and Regression
Linear regression modeling was used to determine any correlations between mouse weights and average tumor volume.

## Reflections on Data:
1. Capomulin and Ramicane appear to have the most promising results. The data shows the average final tumor volumes were not only smaller when compared to the other drug regimens, but the tumor volumes had less variation and a lower standard error value (meaning the results are more reliable when making future predictions). <p>
2. With that said, Capomulin and Ramicane were also the two drug regimens with the highest number of measurements, making them more reliable solely based on the fact that they had more data. Therefore, this could lead to unintended bias in favor of these two drug regimens. Further analysis on other drug regimens should be conducted to help account for bias. <p>
3. When looking at the Capomulin group, there is a slight positive correlation with average tumor volume and mouse weights. Further analysis of average tumor volumes versus mouse weights should be conducted on the other drug groups to see if this correlation is consistent among all experiment groups.
