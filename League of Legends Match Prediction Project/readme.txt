This project involves predicting the outcome of League of Legends matches based on various game-related features. The analysis focuses on different time points (15, 20, 25, and 30 minutes) to understand how predictability evolves as a match progresses.
Introduction

League of Legends is a popular online multiplayer game, and predicting match outcomes is a challenging task. This project utilizes logistic regression to predict match results at different time intervals. The analysis includes Brier Score calculation, accuracy assessment, and feature importance analysis.
Dataset

The dataset consists of game-related features, such as gold differentials, experience differentials, and various in-game events. Data is collected at 15, 20, 25, and 30-minute intervals for both bronze and diamond player matches.
Setup

    Ensure you have the necessary dependencies installed. (NumPy, Pandas, Scikit-learn)
    Run the provided Jupyter notebook to execute the logistic regression models.

Analysis
Brier Score and Accuracy Analysis

The Brier Scores decrease over time, indicating increased predictability as matches progress. Bronze players show lower Brier Scores compared to diamond players, suggesting higher predictability in lower-skilled games.
Feature Importance Analysis

Top 5 features for predicting outcomes (gold_diff, blue_gold, red_gold, xp_diff, red_xp) remain consistent across different time points. Notably, gold_diff is consistently the most influential feature.
Correlation Analysis

A correlation matrix can be computed to understand how feature importance scores correlate across different time points.
Results

    Matches become more predictable over time.
    Bronze player games are generally more predictable than diamond player games.
    Gold difference consistently emerges as the most important feature.

Conclusion

This project provides insights into predicting League of Legends match outcomes and understanding the evolving importance of features over time.
