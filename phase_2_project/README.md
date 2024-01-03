<![Headerimage](./Charts%20%26%20Images/Image1.jpg)

# Phase 2 Project - Analysis of House Sales in King County, WA

**Author: Group 17**

## Overview


## Business and Data Understanding

BuildKesho Consultancy Ltd is pioneering personalized homebuying advice in the King County real estate market. Our focus is on developing a predictive model that not only forecasts house prices but also identifies key property features influencing market valuation. This data-driven approach aims to empower clients with valuable insights, guiding them towards informed investment decisions. 

Our stakeholders include prospective homebuyers and investors seeking expert advice, ensuring they make sound choices in the competitive King County real estate landscape.  

The data source for this analysis is the King County House Sales dataset, kc_house_data.csv, which contains information about the price, location, size, condition and other features of houses sold in King County from January 2014 to December 2015.  

## Modelling

#### Data Cleaning and Analysis

In the process of preparing the data for analysis, the following steps were taken:

- Identified the data types of each column to understand the dataset's structure.
- Dropped irrelevant columns that would not contribute to the modeling process, such as 'date,' 'view,' 'sqft_above,' 'sqft_basement,' 'yr_renovated,' 'zipcode,' 'lat,' 'long,' 'sqft_living15,' and 'sqft_lot15.'
- Checked for null values in the remaining columns and handled them appropriately.
- Ensured the dataset is ready for modeling by addressing data types and missing values.

## Regression Results

- The multiple linear regression model was employed to predict house prices based on various independent variables. The model includes features such as bedrooms, bathrooms, square footage of living space, lot size, floors, year built, condition, grade and waterfront presence.

The results of the regression analysis are as follows:

- R-squared: The model explains approximately 65% of the variance in house prices, indicating a good fit.

Coefficients:

- Bedrooms: Each additional bedroom decreases the estimated house value by $42,820.
- Bathrooms: Each additional bathroom increases the estimated house value by $50,430.
- Sqft_living: An increase in living space by one square foot increases the estimated value by $180.
- Other coefficients for floors, condition, grade and waterfront presence are also significant.

## Findings

Based on the model we have established that houses with the following features tend to have a higher value:

1. The higher the grade assigned to a house, the higher its estimated value. An upgrade to the next grade corresponds to an increase of 13,010 USD in the estimated value.

2. A house with a waterfront increases the estimated value of the house by 75,150 USD.

3. Each additional bathroom in a house corresponds to an estimated value increase of 50,430 USD

4. An increase in the sqft_living of a home will increase the estimated value by 180 USD per sqft

5. An increment of one floor in a house leads to an estimated value increase of 21,650 USD


## Conclusion

In conclusion, the multiple regression model provides valuable insights into the factors influencing house prices in King County. The recommendations below, derived from the model can be utilized by potential homebuyers, investors and BuildKesho Consultancy Ltd to make informed decisions in the real estate market:

1. Stakeholders should prioritize understanding and enhancing grade score descriptions. Consideration of luxurious amenities, up-to-date building plans and meticulous attention to exterior and interior finishes can significantly contribute to increased home value.

2. Stakeholders are advised to prioritize properties with waterfront features to capitalize on the considerable estimated value boost

3. Where feasible, have additional bathrooms as this significantly boosts the estimated value of the house, with each extra bathroom contributing an increase of 50,430 USD

4. Increasing the living space of a home is associated with a positive impact on its estimated value. Consider renovation or expansion projects to capitalize on this potential value increase

5. If applicable, properties with multiple floors exhibit a higher estimated value. Exploring or investing in homes with multiple floors could be a worthwhile consideration.



## For More Information

See the full analysis in the ... or review this .....


## Repository Structure

```
├── Charts & Images
├── Data
├── DSC-PHASE2-PROJECT.ipynb
├── DSC-Phase2-Project-Presentation.pdf
└── README.md
```
