
# E-commerce Data Analysis

This Jupyter Notebook contains a comprehensive analysis of an e-commerce dataset. The analysis includes data cleaning, transformation, and various insights derived from the data. The dataset is loaded from a CSV file and processed using Python libraries such as pandas, numpy, matplotlib, seaborn, and MySQL connector.


## Introduction

This notebook aims to analyze an e-commerce dataset to derive meaningful insights that can help improve sales and customer engagement. The dataset includes information about products, reviews, ratings, prices, and discounts.

## Data Loading and Preprocessing

The dataset is loaded from a CSV file named `amazon.csv`. The following preprocessing steps are performed:

- Handling missing values in the `rating` column by replacing them with the mean.
- Converting price-related columns (`discounted_price`, `actual_price`, `discount_percentage`) to numeric types.
- Encoding categorical columns using `LabelEncoder`.
- Adding new columns such as `discount_amount` and `review_year`.

## Data Analysis

The analysis includes:

- Displaying the first few rows and understanding the data structure.
- Checking for missing values and handling them appropriately.
- Converting relevant columns to numeric types for further analysis.
- Extracting and encoding product categories.

## Database Operations

The processed data is inserted into a MySQL database named `ecommerce_db`. The following operations are performed:

- Creating a database and using it.
- Creating a table named `products` to store the data.
- Inserting the data into the `products` table.
- Executing various SQL queries to retrieve insights from the database.

## Visualizations

Several visualizations are created to understand the data better:

- Distribution of ratings using a histogram.
- Correlation between discount percentage and rating using a scatter plot with a regression line.
- Top 10 highest-rated products using a bar chart.
- Discount percentage vs. rating using a scatter plot.
- Top 5 best-selling categories by total reviews using a pie chart.
- Correlation heatmap of numerical columns.

## Insights and Recommendations

Based on the analysis, the following strategies are recommended to improve sales and customer engagement:

1. Leverage high-performing categories.
2. Enhance product listings.
3. Encourage customer reviews and ratings.
4. Implement personalized marketing.
5. Engage with customers on social media.
6. Implement loyalty programs.
7. Optimize for mobile.
8. Improve customer support.
9. Plan seasonal promotions and sales.
10. Continuously analyze and adapt strategies.

## Anomalies and Patterns

Several anomalies and patterns are identified in the data:

- Missing values in the `rating_count` and `review_year` columns.
- Data type issues in price-related columns.
- High discount percentages indicating aggressive discounting strategies.
- High customer engagement in certain categories.
- Significant correlation between discount percentage and rating.
- Highly reviewed products dominating customer attention.
- High average ratings in specific categories.
- Significant discount amounts on many products.
- Missing values in the `review_year` column.

These insights can be used to improve data processing and business strategies.

## Author

**Sarah Sindet**
