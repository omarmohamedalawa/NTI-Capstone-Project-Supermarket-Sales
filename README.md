# Supermarket Sales Analysis

## Project Overview
This project aims to analyze a supermarket sales dataset, clean the data, and extract insights to better understand customer behavior, product preferences, and sales trends. The analysis covers sales distribution across branches, rush hours, customer types, and product categories.

## Dataset Description
The dataset consists of transactional records from a supermarket with the following key attributes:
- **Invoice ID**: Unique identifier for each transaction.
- **Branch**: The branch where the transaction occurred (A, B, C).
- **Customer Type**: Normal or Member customers.
- **Gender**: Gender of the customer.
- **Product Line**: Category of the products purchased.
- **Unit Price**: Price of each product.
- **Quantity**: Number of items bought in a transaction.
- **Tax 5%**: The tax amount applied to the total price.
- **Total Cost**: Total amount including tax.
- **Date**: The date of the transaction.
- **Time**: The time of the transaction.
- **Payment**: Payment method used (Cash, Credit Card, E-wallet).
- **Rating**: Customer satisfaction rating.
- **City**: The city in which the transaction occurred.

## Objectives
The main objectives of this project include:
- Cleaning the dataset by handling missing values, correcting outliers, and removing duplicates.
- Analyzing the relationship between different attributes such as total sales, branches, and customer types.
- Visualizing key insights such as rush hours, sales distribution, and total sales per branch.

## Technologies Used
- **Pandas**: Used for data manipulation and cleaning.
- **Matplotlib**: For creating visualizations.
- **Jupyter Notebook**: The development environment for running the analysis.
- **PowerBI**: The analysis and visualization were conducted using PowerBI.

## Data Cleaning Process
1. **Missing Values**:
   - Filled missing data in the Customer Type column and corrected incorrect entries like "memberr".
   - Recalculated missing values in Total Cost and Tax columns based on the unit price and quantity.
2. **Outliers**:
   - Corrected outliers in the Rating column (e.g., 97 instead of 9.7).
   - Fixed negative values in Quantity.
3. **Duplicate Records**:
   - Removed six duplicate records from the dataset.
4. **Tidiness Issues**:
   - Combined separate city columns into one City column for easier analysis.

## Visualizations
1. **Scatter Plot of Unit Price vs. Total Cost**:
   - Shows the relationship between the unit price of products and the total cost of transactions.
2. **Rush Hour Analysis**:
   - Scatter plot identifying peak hours based on the number of users (transactions) per hour.
3. **Total Sales by Branch**:
   - Bar chart visualizing the total sales for each branch, helping identify the best-performing branch.

## Dashboard
![Dashboard_of_Supermarket_Sales_Project_page-0001](https://github.com/user-attachments/assets/bd39fc69-9738-442a-8b30-7d6a70d54734)
![Dashboard_of_Supermarket_Sales_Project_page-0002](https://github.com/user-attachments/assets/810a2002-fce2-44a7-9636-176dc9e31bcc)
![Dashboard_of_Supermarket_Sales_Project_page-0003](https://github.com/user-attachments/assets/49ead21a-3f77-464a-a337-3a4bb537fe3d)
![Dashboard_of_Supermarket_Sales_Project_page-0004](https://github.com/user-attachments/assets/5a7f8b20-573d-45fe-85ea-72327e794ea8)
![Dashboard_of_Supermarket_Sales_Project_page-0005](https://github.com/user-attachments/assets/f8ad0ed5-f4d2-4343-a62a-d9f489af849d)



## How to Run the Project
1. Clone or download the repository.
2. Open the Jupyter Notebook file.
3. Run the notebook to view the data cleaning, analysis, and visualizations.

## Conclusion
The analysis provides valuable insights into customer behavior, sales trends, and rush hour traffic, which can help optimize marketing strategies and operational efficiency for the supermarket.

