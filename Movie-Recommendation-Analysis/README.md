An interactive Exploratory Data Analysis (EDA) project on Electric Vehicles using Python, Pandas, Seaborn, Matplotlib, and Plotly.

![Project Banner](![Uploading car.jpeg…]())

## 📋 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [Results](#results)
- [How to Run](#how-to-run)
- [Author](#author)

#### Overview

This project performs a comprehensive analysis of Electric Vehicles (EVs) data, focusing on understanding market trends, manufacturer dominance, electric range distribution, and the shift between Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).

#### Dataset

- **Source**: Washington State Department of Licensing (DOL) - Electric Vehicle Population Data
- **Size**: 177,866 records
- **Time Period**: 1997 - 2024
- **Key Columns**: Make, Model, Model Year, Electric Vehicle Type, Electric Range, Base MSRP, County, City, etc.

#### Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Manufacturer and model analysis
- Comparison between BEV and PHEV
- Electric range analysis
- Interactive visualizations using Plotly

#### Technologies Used

- **Python**
- **Pandas** - Data manipulation
- **NumPy**
- **Matplotlib & Seaborn** - Static visualizations
- **Plotly** - Interactive visualizations

#### Key Insights

- **Tesla** is the dominant manufacturer in the EV market.
- **Model Y** and **Model 3** are the most popular models.
- Battery Electric Vehicles (BEVs) significantly outperform Plug-in Hybrid Electric Vehicles (PHEVs) in electric range.
- Most vehicles have moderate electric ranges (200–300 miles), with few high-range outliers.
- Newer model years do not always guarantee significantly higher electric ranges.
- The market is clearly shifting toward fully electric (BEV) vehicles.

#### Visualizations

- Top 10 EV Manufacturers (Count Plot)
- Treemap: Electric Range by Vehicle Type, CAFV Eligibility, and Make
- Sunburst Chart: Electric Range by Make, Model, and Vehicle Type
- Distribution plots and trend analysis

#### Results

- Tesla dominates the EV market in Washington.
- Model Y is the clear leader among all models.
- BEVs have significantly higher average electric range than PHEVs.
- Clean Alternative Fuel Vehicle (CAFV) eligible vehicles tend to have better range.
- The EV market is growing rapidly with newer models.
