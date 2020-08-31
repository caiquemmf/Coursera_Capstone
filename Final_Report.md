# FINAL REPORT - Capstone Project
This is the final report, with the goal of classifying the severity of a collision, based on the data gathered from previous collisions.

## Introduction
Seattle's traffic department has data since 2004 about collisions that happened in the city. They want to use Machine Learning to create a model of classification for the severity of the collisions based on the data collected about them.

## Data Understanding
From the data available, the following variables will be used, based on the correlation and feasibility of their effectiveness. The variables used will be mostly categorical ones, like: type of collision, collision address type, weather, road condition, light condition, type of juction, day of the week, alcohol influence and collision code.
These variables will help to predict the severity of the collision.

# Data preparation
Null values were replaced with the average or most frequent value for the quantitative and qualitative variables. The day of the week, retrieved from the manipulation of the date, was added as a dependent variable. The last step was transforming all the qualitative data into quantitative and normalizing it.

## Methodology
Different strategies were tested to highlight the relationship between the dependent and target variables. Out of linear regression, support vector machines, decision trees and k-nearest neighbors, the last showed higher score on predicting the severity, based on Jaccard and F1-Score evaluation methods.

# Results
The selected model can predict with ~70%+ the type of severity based on the selected dependent variables.

# Conclusion
This approach led to the discovery of significant variables that can possibly predict the severity of the accidents. 
