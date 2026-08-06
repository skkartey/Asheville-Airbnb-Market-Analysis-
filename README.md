# Asheville Airbnb Market Analysis

## Project Overview

This project analyzes the Asheville, North Carolina Airbnb market to identify factors that influence listing performance, including pricing, occupancy, location, property size, and guest reviews.

Using data from Inside Airbnb, we conducted exploratory data analysis (EDA), feature engineering, correlation analysis, and data visualization to examine market supply and demand and identify factors associated with estimated monthly revenue.

## Objectives

The analysis focuses on several key questions:

- How does listing price relate to occupancy rate?
- Which factors are associated with higher estimated monthly revenue?
- How does listing performance vary across Asheville neighborhoods?
- What relationship exists between property size and revenue?
- How do guest reviews relate to pricing and booking activity?

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data

The analysis uses listing, calendar, and review data from Inside Airbnb.

Due to GitHub file-size limitations, the full raw datasets containing reviews are not included in this repository .

## Analysis

### Exploratory Data Analysis

Exploratory analysis was conducted to examine the distributions of listing prices, occupancy rates, reviews, ratings, and estimated monthly revenue.

Scatter plots, box plots, bar charts, and a correlation matrix were used to identify relationships and outliers within the market.

### Feature Engineering

Two key performance measures were developed:

- **Occupancy Rate** — calculated by combining listing and calendar availability data.
- **Estimated Monthly Revenue** — calculated using average nightly price and estimated booked days per month.

## Key Findings

- **Price and revenue:** Price had a strong positive correlation (0.74) with estimated monthly revenue.
- **Price and occupancy:** Price had a very weak negative correlation (-0.046) with occupancy rate.
- **Location:** Revenue varied substantially across Asheville neighborhoods, indicating that location plays an important role in listing performance.
- **Property size:** Listings with more bedrooms generally generated higher revenue, although several smaller properties substantially outperformed typical listings.
- **Reviews and pricing:** Listings with larger numbers of reviews tended to have lower prices, while many high-priced listings had fewer reviews.
  ## Selected Visualizations

### Correlation Analysis

![Correlation Matrix](images/Correlation%20Matrix.png)

The correlation analysis shows a strong positive relationship between price and estimated monthly revenue (0.74), while price and occupancy rate have almost no linear relationship (-0.046).

### Price vs. Occupancy Rate

![Price vs. Occupancy Rate](images/price_vs_occupancy.png)

Most bookings are concentrated among lower-priced listings, while occupancy varies considerably across the market.

### Revenue by Neighborhood

![Median Monthly Revenue by Neighborhood](images/monthly_revenue.png)

Median estimated monthly revenue varies across Asheville neighborhoods, highlighting location as an important factor in listing performance.

## Business Recommendations

Based on the analysis, Airbnb hosts could:

- Use dynamic pricing strategies to respond to changes in market demand.
- Focus on guest experience and reviews to encourage booking activity.
- Invest in amenities or unique property features that differentiate listings.
- Consider neighborhood-level performance when purchasing or marketing short-term rental properties.

## Repository Contents

- **Asheville Airbnb Analysis.ipynb** — Python code, data preparation, analysis, and visualizations
- **Visualizations.pdf** — Selected visual outputs from the analysis
- **Asheville Airbnb Market Analysis Report.pdf** — Full project report

## Authors

Sedinam Kartey and project team  
UNC Charlotte  

