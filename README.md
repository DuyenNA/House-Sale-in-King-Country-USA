# House Sales in King County, USA ![house-emoji](https://user-images.githubusercontent.com/124249298/230869647-ca683212-400a-42fd-81fc-3e8b08c8a797.png)

This project is an analysis of the house sales data for King County, USA. The goal of this project is to analyze the data and provide insights into the factors that affect house prices in this area. The data set used in this project contains information on house sales from May 2014 to May 2015.

# Data Set

The data set used in this project can be found in the file "kc_house_data.csv" from Kaggle. It contains the following variables:
- id: A unique identifier for each house sold
- date: The date on which the house was sold
- price: The price at which the house was sold
- bedrooms: The number of bedrooms in the house
- bathrooms: The number of bathrooms in the house
- sqft_living: The square footage of the living area of the house
- sqft_lot: The square footage of the lot on which the house is situated
- floors: The number of floors in the house
- waterfront: A binary variable indicating whether the house has a view of the waterfront or not
- view: An index from 0 to 4 of how good the view of the property was
- condition: An index from 1 to 5 on the condition of the house
- grade: An index from 1 to 13 on the overall grade given to the housing unit, based on King County grading system
- sqft_above: The square footage of the house apart from the basement
- sqft_basement: The square footage of the basement
- yr_built: The year the house was built
- yr_renovated: The year the house was renovated (0 if never)
- zipcode: The zipcode of the area in which the house is located
- lat: The latitude of the location of the house
- long: The longitude of the location of the house
- sqft_living15: The average square footage of the interior living space of the nearest 15 neighbors
- sqft_lot15: The average square footage of the land lots of the nearest 15 neighbors

# Analysis

This data set is analyzed using Python and its data analysis and visualization libraries as Matplotlib and Seaborn. The main analysis steps include:

- Data cleaning and exploration
- Correlation analysis
- Model building and evaluation
The analysis is documented in the Jupyter notebook https://github.com/DuyenNA/House-Sale-in-King-Country-USA/blob/main/House_Sales_in_King_Country_USA.ipynb, which contains code, visualizations, and explanations of the analysis steps.

# Results

The results of the analysis include insights into the factors that affect house prices in King County, USA. Some of the key findings include:
- Square footage of the living area has a strong positive correlation with house prices.
- A view of the waterfront or a good view of the property significantly increases the house price.
- The house grade also has a strong positive correlation with house prices.
- A linear regression model can be used to predict house prices with a high degree of accuracy, the predicted result indicates average house price will not change much.

# Conclusion ![test-passed](https://user-images.githubusercontent.com/124249298/230869568-ebe5d9e7-57d2-4cfe-903f-7b267daa1a4e.png)


In conclusion, this analysis provides valuable insights into the factors that affect house prices in King County, USA. The results can be used by real estate agents, buyers, and sellers to make informed decisions about buying or selling a house in this area.
