# Video Game Sales Analysis: Market Trends, Regional Preferences, and Hit Prediction
Author: Tin Trung Nguyen

## Introduction
The video game industry is one of the largest entertainment markets in the world, with thousands of titles released across multiple platforms each year. Understanding what drives the commercial success of video games can provide valuable insights for developers, publishers, and market analysts.

This project analyzes historical video game sales data to explore trends in the gaming market. Using exploratory data analysis (EDA), statistical methods, machine learning models, and interactive dashboards, the project investigates the factors that influence game sales and market performance.

## Motivation

This project aims to apply a complete data science workflow to a real-world dataset from the gaming industry.

The analysis focuses on uncovering patterns in game success and exploring how factors such as genre, platform, publisher, and critic scores relate to sales performance. It also serves as a hands-on project demonstrating skills in data analysis, statistical testing, predictive modeling, and data visualization.

## Research Questions

This project explores several key questions:
How have video game sales evolved over time?
Which genres, platforms, and publishers generate the highest sales?
Are there regional differences in gaming preferences?
Do higher critic scores correlate with higher sales?
Can we predict whether a game will become commercially successful?

## Methods

The project combines several data science techniques:

**Exploratory Data Analysis**

- Sales distribution and market trends
- Genre, platform, and publisher performance
- Regional sales comparisons

**Statistical Analysis**

- Correlation analysis
- Hypothesis testing
- Group comparisons across genres and regions

**Machine Learning**

- Regression models for predicting game sales
- Classification models for predicting hit games

**Visualization**

- Python plots for analysis
- Tableau dashboards for interactive exploration

## Key Findings

Critic scores show a **positive but weak relationship with sales**, indicating that while **higher-rated games tend to sell better**, reviews alone are not strong predictors of commercial success.

**Genre plays a major role in revenue generation**, with Sports, Action, and Shooter games **producing the highest total sales** across the dataset.

**Console platform significantly impacts game performance**, with consoles such as PlayStation 2, Xbox 360, and PlayStation 3 generating the **highest cumulative sales**.

**Regional gaming preferences differ**, with North America dominating overall sales, while Japan shows stronger interest in genres such as Role-Playing and Visual Novel games.

**Publisher reputation also influences success**, as companies like Rockstar Games and Activision demonstrate higher average sales per title due to popular blockbuster franchises.

Machine learning models achieved moderate predictive performance, suggesting that while available features provide useful signals, other factors such as marketing, franchise popularity, and brand recognition likely contribute significantly to game sales.

## Dependencies

Python libraries used in this project:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

## Project Structure
gamessales_project/
    dataset/
        VideoGames_Sales.xlsx
        cleaned/
            clean.csv
    notebooks/
        preprocessing.ipynb
        eda.ipynb
        stats.ipynb
        modelling.ipynb
    README.md