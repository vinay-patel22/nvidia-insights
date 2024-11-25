# Stock Market Analysis of Nvidia Corporation

## Overview

This project analyzes the stock price trends of Nvidia Corporation using historical data to derive insights into market performance, volatility, and investment opportunities.

## Dataset

Download the dataset from Kaggle: [Nvidia Stocks Data](https://www.kaggle.com/datasets/kpatel00/nvidia-stocks-data-latest-25-august-2024/)

## Table of Contents

- [Introduction](#introduction)
- [Data Preparation](#data-preparation)
- [Analytical Techniques](#analytical-techniques)
- [Visualizations](#visualizations)
- [Comparative Analysis](#comparative-analysis)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)
- [Future Work](#future-work)

## Introduction

The primary objective of this project is to conduct a comprehensive analysis of Nvidia's stock prices, providing insights into trends and potential trading strategies.

## Data Preparation

- Loaded and cleaned historical stock price data from a CSV file.
- Converted the 'Date' column to datetime format and set it as the index.
- Created additional features, including:
  - **Daily Returns**: Percentage change from the previous closing price.
  - **Volatility**: 30-day rolling standard deviation of daily returns.

## Analytical Techniques

- **Moving Averages**: Implemented 50-day and 200-day moving averages to identify market trends.
- **Bollinger Bands**: Analyzed price volatility and potential reversals.
- **Cumulative Returns**: Evaluated overall investment growth over time.

## Visualizations

- Developed various visualizations to represent:
  - Daily returns distribution and volatility trends.
  - Trading volume over time.
  - Stakeholder visualizations combining price trends and volume.

## Comparative Analysis

- Compared Nvidia's stock performance with Advanced Micro Devices (AMD) to assess market positioning.

## Key Insights

- Identified key trends and potential trading signals based on moving averages and volatility.
- Delivered actionable insights for stakeholders to guide investment strategies.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly

## Future Work

- Explore advanced statistical modeling and machine learning techniques for predictive analysis.
- Expand the analysis to include additional semiconductor companies for a broader market view.

## License

This project is licensed under the MIT License.
