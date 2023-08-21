# Exploratory Data Analysis on Seattle Airbnb Data

## Table of Contents

- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Data Wrangling](#data-wrangling)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Conclusions](#conclusions)

## Introduction

Welcome to the Exploratory Data Analysis (EDA) report on the Seattle Airbnb dataset. In this project, we delve into the world of Airbnb listings in Seattle, WA, to uncover insights, trends, and patterns that are hidden within the data. By performing a thorough analysis, we aim to gain a better understanding of the factors that influence pricing, occupancy, and customer reviews.

## Dataset Description

The dataset comprises three main files:

1. `listing.csv`: Contains information about hosts, prices, room types, property types, and more for 3818 Airbnb listings in Seattle. It has 44 columns with varying degrees of missing data.
2. `calendar.csv`: Provides information about occupancy and availability for 2873 listings every day from January 2016 to January 2017. It includes the listing ID, date, availability (t: available, f: occupied), and price.
3. `reviews.csv`: Contains approximately 85k reviews for each property from 2009-2016, with details like reviewer ID, reviewer name, and comments.

## Data Wrangling

In this section, the dataset underwent preprocessing and cleaning to ensure it was ready for analysis. Some key actions taken included:

- Merging relevant datasets to consolidate information.
- Handling missing values by either dropping or imputing them as appropriate.
- Converting columns like prices from string format to numeric values for analysis.
- Creating new features to capture insights, such as the presence of a security deposit.

## Exploratory Data Analysis

The EDA section is the heart of the report, where we dig deep into the data to uncover meaningful insights. Some of the analyses and visualizations performed include:

- Exploring the distribution of listing prices, occupancy, and review scores.
- Identifying trends in availability and occupancy over the year.
- Investigating the impact of various features (e.g., neighborhood, amenities) on listing prices.
- Correlating review scores with other factors to determine what affects guest satisfaction.

## Conclusions

After thorough analysis, we've gained valuable insights into the Seattle Airbnb market:

- The dataset contains 3818 listings provided by 2751 hosts.
- Missing data is present in various columns, and certain features have a high percentage of missing values.
- Availability and prices follow seasonal trends, with peaks and troughs over the year.
- Specific features like neighborhood, amenities, and room type have a significant impact on listing prices.
- Factors like cleanliness, communication, and location are correlated with higher review scores.

This EDA report uncovers essential patterns and trends in the Seattle Airbnb dataset, providing a foundation for further analysis and decision-making in the vacation rental industry. We hope these findings provide valuable insights for potential hosts, guests, and stakeholders in the Seattle Airbnb market.

Feel free to explore the code and visualizations provided in the analysis section for a deeper understanding of the insights gained.

## Author

[Amanda Akerele]

## Acknowledgments

Special thanks to the https://www.kaggle.com/datasets/airbnb/seattle for providing this rich dataset, enabling us to conduct this exploratory analysis.

---

Feel free to customize this template to match the specifics of your EDA report. Include additional sections, visuals, or explanations as needed to accurately convey the details of your analysis.
