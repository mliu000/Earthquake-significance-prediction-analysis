﻿# Earthquake Significance/Impactfulness prediction analysis side project. 

***Abstract***

Motivation: 

Earthquakes happen every year. Many earthquakes are harmless, while some are devastating. For the dataset that we used, each earthquake was given a significance score, while typically ranges between 400-1200. The higher the score, the more impactful/damaging the earthquake is. All earthquakes had parameters such as their Magnitude, Modified Mercalli intensity (mmi), depth of shaking, whether or not a tsunami was generated, etc recorded. The main goal of this analysis is to accurately predict the significance score based on those parameters. This can be useful because if a new earthquake occurs, the magnitude, etc, can be recorded right away, but the damage/impact takes time to fully show. Having a forecast of the significance of an earthquake first responders to effeciently plan and distribute resources such as first aid and safety equipment, predict casualty rates (if any), and estimate the total economical impact of affected areas. Thus, having social and economical implications. 

Process Outline: 

Based on all given variables for each earthquake in the dataset, we took 5 of them seemingly most useful ones (which include magnitude and mmi), and analyzed the data. Out of the variables that were chosen, we first did some exploratory analysis to determine which variables were correlated in some way with the significance score, while removing the variables that did not have much effect. Afterwards, we decided to use a kNN regression model, and perfomed a 5-fold cross validation to determine the best k. A sample prediction was also demonstrated. Lastly, as with any data analysis, the our methodology had both pros and cons, which were discussed in the end. 

This project was done with a friend. Complete progress can be found in the respository: https://github.com/EdmundChuu/Earthquake

The entire analysis (including visualizations) can be found in the **Earthquake_Analysis.ipynb** file. The programming language of choice is **Python**.
