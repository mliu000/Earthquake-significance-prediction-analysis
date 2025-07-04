# Earthquake Significance / Impact Prediction Analysis

## Motivation

Every year, earthquakes occur all over the world. While many are harmless, some can be devastating. In the dataset we worked with, each earthquake was assigned a **significance score** (usually between 400–1200) — the higher the score, the more damaging or impactful the earthquake was considered to be.

Each earthquake also came with parameters like:
- Magnitude  
- Depth  
- Modified Mercalli Intensity (MMI)  
- Whether a tsunami occurred  
- and more.

The goal of our analysis was to see whether we could **predict the significance score** using these variables. This has useful real-world implications: when a new earthquake hits, we can immediately collect physical parameters (like magnitude and depth), but we won’t know the full impact for days. A good forecast could help emergency responders plan more efficiently — from distributing first aid to estimating casualties or economic loss.

## What We Did

We started by selecting five variables we thought would be the most informative — including **magnitude** and **MMI**. We ran some basic exploratory data analysis (EDA) to see which variables correlated with the significance score and removed those that didn’t seem useful.

Then we trained a **K-Nearest Neighbours (kNN) regression model**, and used **5-fold cross-validation** to find the best `k`. Finally, we generated a sample prediction and discussed some of the strengths and weaknesses of our approach.

## Tools & Tech Used

- **Language:** Python  
- **Notebook:** Jupyter  
- **Libraries:** pandas, matplotlib, seaborn, scikit-learn  
- **Model:** kNN regression

## Files

- `Earthquake_Analysis.ipynb` → Our full analysis, EDA, modeling, and visualizations.

## Collaborators

This was a small side project done with a friend. You can find the full repository here:  
🔗 https://github.com/EdmundChuu/Earthquake

## Notes*

This isn’t a production-grade model, and it has some limitations (like small dataset size, lack of time series features, etc). But it was a fun and meaningful way to explore predictive modeling on real-world data.