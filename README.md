# Forecasting UEFA Champions League Team Success using Multiple Linear Regression

## Project Overview
This project aims to enhance strategic decision-making in sports organizations by predicting the performance outcomes of UEFA Champions League teams through statistical modeling.

## Objectives
Develop a multiple linear regression model to predict the win and possession percentages for teams in the 2021/22 UEFA Champions League season.

## Dataset
- The analysis is based on data from 32 soccer teams, featuring detailed historical performance metrics such as team names, wins, goals, and more.
- Data preprocessing involved fixing data types, dropping irrelevant columns, and creating new metrics like win percentage.

## Methodology
- Model Selection Techniques: Step-wise, Forward, Backward, and Best Subset Selection were used to identify optimal predictive models.
- Assumption Checks: Validated models on criteria such as multicollinearity, equal variance, linearity, and normality.
- Model Refinement: Included interaction and higher order terms, with iterative refinement to handle issues like multicollinearity.

## Models Developed
- Win Percentage Model: Achieved an Adjusted R-Squared of 0.84, showing strong predictive capability.
- Possession Percentage Model: Yielded an even higher Adjusted R-Squared of 0.92, indicating excellent model fit.

## Results
- Models were validated using real tournament data, accurately predicting outcomes for teams like Manchester City and AC Milan.
- Both models satisfied all statistical assumptions, confirming their robustness and reliability.

## Conclusion
The developed regression models successfully predict key performance indicators for football teams, demonstrating potential applications in sports analytics for team performance optimization.
