# Exploring Real Estate Evaluations with Advanced ML Techniques

## Overview

This project analyzes property-level housing data sourced from realtor.com, featuring over 1 million current listings as of 12/5, mainly in the northeastern United States. The dataset includes details like bedrooms, bathrooms, square footage, lot size, price, recent sale date, location, and house availability status. The analysis encompasses various exploratory and analytical models to extract insights.

## Objectives

1. **Regression Models:**
   - Explored regression models to predict house prices based on attributes.
   - Tuned hyperparameters for model improvement.

2. **Income Bracket Comparison:**
   - Utilized IRS data for zipcode-level income information.
   - Compared house prices with average income brackets for regions.

3. **Home Value Index Analysis:**
   - Integrated Zillow's time series data for estimated home value indices at the zip code level.
   - Classified properties as overpriced, underpriced, or reasonably priced.

4. **Classification Models:**
   - Trained and tested classification models, including a neural network.
   - Used property attributes for overpriced or underpriced classification.

## Data Sources

- **Realtor.com Data:** Property-level housing data with attributes. [Dataset Link](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)
- **IRS Data:** Zipcode-level income data. [Dataset Link](https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-zip-code-data-soi)
- **Zillow Data:** Time series data for estimated home value indices. [Dataset Link](https://www.zillow.com/research/data/)

## Results

This analysis uncovers insights into factors influencing house prices, compares them with income data, and classifies properties based on estimated value. Final models reveal attributes perceived as more valuable than the market suggests.

## Contributors

- Brendan Nguyen (bmnguyen@seas.upenn.edu)
- Atharv Awasthi (@aawas22@seas.upenn.edu)
