# Exploratory Data Analysis (EDA) on Amazon Sales Dataset

This repository contains code and analysis for performing Exploratory Data Analysis (EDA) on the Amazon Sales Dataset. The dataset contains various  information on 1K+ Amazon products, including their ratings, reviews, and other details

## Dataset

This dataset is having the data of 1K+ Amazon Product's Ratings and Reviews as per their details listed on the official website of Amazon

### Features

- product_id : Unique identifier for each product
- product_name :  Name of the Product
- category : Category of the Product
- discounted_price : Discounted Price of the Product
- actual_price : Actual Price of the Product
- discount_percentage : Percentage of Discount for the Product
- rating : Rating of the Product (1-5)
- rating_count : Number of people who voted for the Amazon rating
- about_product : Description about the Product
- user_id : ID of the user who wrote review for the Product
- user_name : Name of the user who wrote review for the Product
- review_id : ID of the user review
- review_title : Short review
- review_content : Long review
- img_link : Image Link of the Product
- product_link : Official Website Link of the Product

## Contents
- `amazon.csv`: CSV file containing the dataset.
- `amazon_eda.ipynb`: Jupyter Notebook containing the code for EDA.
- `README.md`: This README file providing an overview of the repository.

## Analysis
The EDA focuses on understanding the distribution and relationships between various clinical parameters in the dataset. Key aspects of the analysis include:
- Data cleaning and preprocessing.
- Univariate analysis to understand the distribution of individual features.
- Bivariate analysis to explore relationships between pairs of features.
- Visualization of findings using plots such as histograms, box plots, and scatter plots.

## Findings
1. What is the average rating for each product category ?
2. What are the top rating_count products by category ?
3. What is the distribution of discounted prices vs. actual prices ?
4. How does the average discount percentage vary across categories?
5. What are the most popular product names?
6. What are the most popular product keywords?
7. What are the most popular product reviews?
8. What is the correlation between discounted_price and rating?
9. What are the Top 5 categories based on the highest ratings?
10. Identify any potential areas for improvement or optimization based on the data analysis.


## Requirements
To run the analysis, you need Python 3.x along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

You can install the required libraries using pip:
```
pip install pandas numpy matplotlib seaborn jupyter
```


