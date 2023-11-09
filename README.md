# Airbnb London Rental Price Prediction Case Study

*Note : The project is still being improved*

## Overview

This repository focuses on a comprehensive case study centered on predicting rental prices for apartments listed on Airbnb in London. The primary objective is to develop a sophisticated predictive model based on discerning property features. This model serves a dual purpose: providing insightful estimations for potential revenue from property investments and facilitating strategic decision-making in the pursuit of reasonably priced accommodations across diverse London neighborhoods.

## Dataset Characteristics

With a dataset encompassing a substantial 51,646 observations, our analysis is concentrated on 33 London boroughs, meticulously selected as variables. The variables under scrutiny span a spectrum of factors, including but not limited to property type, room configuration, and an array of amenities. To streamline the analytical process, variables are meticulously categorized as quantitative (prefixed with "n_"), qualitative (prefixed with "f_") and dummies (prefixex with "d_") forming the foundation for an efficient and nuanced predictive model.

## Key Metrics

- **Dataset Size:** 51,646 observations
- **Variables:** 65 columns
- **Considered Factors:** Property type, room configuration, amenities
- **Variable Classification:** Quantitative (prefixed with "n_"), Qualitative (prefixed with "f_") and Dummies (prefixed with "d_")
- **Target Variable :** 'usd_price_day'

## Purpose and Significance :

The initial step in our approach involves conducting an exploratory analysis to comprehend the data and evaluate the impact of various variables on the target variable. Utilizing the insights gained from this preliminary analysis, we then move on to constructing different prediction models. This approach ultimately empowers us to choose the optimal model, guided by the conclusions drawn from our prior analyses.

## Navigating the Repository

1. **Exploring Data and Visualizing Insights:** Dive deep into the dataset to uncover the intricacies of London's Airbnb market.
2. **Building Models:** Construct multiple models, with each undergoing parameter optimization using a validation set.
3. **Making Predictions:** Test the top-performing models from each category on a generalization set. The model that excels here is the one we'll choose.

---
