# Selecting a Location for a Well #
## Project Overview
This project aims to determine the best location for drilling a new oil well for the mining company GlavRosGosNeft. By analyzing oil samples from three different regions, the goal is to build a machine learning model to identify the region with the greatest potential profit. The analysis includes evaluating potential profits and risks using the Bootstrap technique.

## Introduction
GlavRosGosNeft, a mining company, needs to decide on the optimal location for drilling a new oil well. Data from three regions, each with 10,000 fields, includes measurements of oil quality and reserve volumes. The objective is to analyze this data to maximize profits and minimize risks.

## Problem Statement
Given the oil sample data from three regions, the task is to build a machine learning model to predict the potential profit of drilling in each region. The analysis involves:

* Building a linear regression model.
* Calculating the break-even point for oil production.
* Estimating profits from the 200 most profitable wells in each region.
* Using the Bootstrap technique to assess average profit, 95% confidence intervals, and the risk of loss.
## Data Description
The dataset contains information on:

Oil Quality: Various characteristics indicating the quality of oil.
Reserve Volumes: The volume of oil reserves in barrels for each field.
The data is available for three regions with 10,000 fields each.

## Installation
System Requirements

Operating System: Windows, macOS, or Linux

Python Version: 3.8 or higher
## Required Libraries
The project requires the following Python libraries:

pandas
numpy
scikit-learn
matplotlib
seaborn

## Conclusion
Based on the analysis, Region 1 is the optimal location for drilling due to its lower risk of loss (0.6%) and substantial profit potential (2415.087 million rubles).

## Recommendations
For maximizing profit and minimizing risks, it is recommended to focus on developing oil wells in Region 1. Conduct promotions and allocate resources towards this region to capitalize on its favorable economic prospects.
