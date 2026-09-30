# puerto-rico-real-estate-analysis
Exploratory data analysis of Puerto Rico home listing prices using Python, pandas, Jupyter Notebook, and data visualization.
# Puerto Rico Real Estate Price Analysis

## Project Overview

This project explores factors associated with home listing prices in Puerto Rico. Using Python and a real-estate dataset, I cleaned the data and analyzed how location, number of bedrooms, and home size relate to listing prices.

## Questions Explored

1. What is the distribution of home listing prices in Puerto Rico?
2. Which Puerto Rico cities have the highest average listing prices?
3. Is the number of bedrooms associated with listing price?
4. Do larger homes tend to have higher listing prices?

## Tools Used

- Python
- Jupyter Notebook
- pandas
- Matplotlib
- Seaborn

## Data Preparation

The original dataset included listings from across the United States. For this analysis, I:

- Filtered the data to Puerto Rico properties currently listed for sale
- Removed records with missing values in key columns
- Focused on realistic values for price, bedrooms, bathrooms, and house size to make the analysis and visualizations easier to interpret

## Key Findings

- Most cleaned Puerto Rico listings were priced below $400,000.
- Dorado had the highest average listing price among cities with at least 10 listings.
- The number of bedrooms alone did not have a perfectly consistent relationship with listing price.
- Home size had a moderate positive relationship with listing price: larger homes generally tended to be listed at higher prices.

## Visualizations

The notebook includes:

- A histogram of Puerto Rico home listing prices
- A bar chart of the top 10 cities by average listing price
- A bar chart comparing median listing price by number of bedrooms
- A scatterplot showing the relationship between home size and listing price

## Limitations

This analysis is based on available listings in the dataset and does not represent every property in Puerto Rico. Listing prices may also differ from final sale prices.

## Dataset

USA Real Estate Dataset from [Kaggle](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)

## How to View the Analysis

Open [PR_RealEstate.ipynb](PR_RealEstate.ipynb) to view the complete analysis, code, visualizations, and findings.
