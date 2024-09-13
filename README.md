# Capstone-Project-SuperMarket-Data-Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Analysis and Reports](#analysis-and-reports)
- [Prerequisites](#prerequisites)
- [Installation and Setup](#installation-and-setup)
- [Results and Insights](#results-and-insights)

## Project Overview

The **Supermarket Sales Data Analysis** project aims to delve into a dataset containing transactional records from various supermarket branches. This project focuses on data wrangling, in-depth analysis, and visualization to uncover valuable insights about sales performance, customer behavior, and product trends. By examining the data, we seek to understand patterns in branch performance, customer purchasing habits, and product line profitability. The ultimate goal is to provide actionable recommendations that can help optimize operations, enhance marketing strategies, and improve overall business performance.

## Dataset Description

The project utilizes the "Supermarket Sales" dataset, which includes transactional data from multiple supermarket branches. Key features of the dataset are:

- **Invoice ID:** The ID of the invoice.
- **Branch:** The branch where the invoice originates. Branches include: A ,B ,or C
- **Yangon:** is branch
- **Naypyitaw:** is branch
- **Mandalay:** is branch
- **Customer Type:** The type of customer (Member, Normal).
- **Gender:** The gender of the customer.
- **Product Line:** The product category.
- **Unit Price:** The price per unit of the product.
- **Quantity:** The quantity of the product ordered.
- **Tax 5%:** The total tax applied to the order.
- **Total:** The total amount paid for the invoice.
- **Date:** The date of the invoice.
- **Time:** The time of the invoice.
- **Payment:** The payment method used.
- **Rating:** The customer’s rating of the products.

## Analysis and Reports

### Data Wrangling Notebook

- **Data_Wrangling.ipynb**: A Jupyter notebook that details the data cleaning and preprocessing steps taken to prepare the dataset for analysis.

### Data Wrangling Report

- **Data_Wrangling_Report.pdf**: A document summarizing the data wrangling process, including methods for cleaning, transforming, and organizing the data.

### Business Insights Report

- **Business_Insights_Report.pdf**: A detailed report outlining key business insights derived from the data analysis, with visualizations and interpretations.

### Paginated Report using Power BI

- **Paginated_Report.pbix**: A Power BI report providing detailed, paginated insights into the supermarket sales data.

## Prerequisites

Before setting up the project, ensure you have the following installed on your local machine:

- **Python 3.x**: Programming language used for data wrangling and analysis.
- **Jupyter Notebook**: Tool for running and interacting with the data wrangling notebook.
- **Power BI Desktop**: Application for viewing and interacting with the Power BI report.

## Installation and Setup

To set up the project on your local machine, follow these steps:

1. **Clone the Repository**

   Clone the repository and navigate to the project directory:

   ``` 
   git clone https://github.com/OoZz26/Capstone-Project-SuperMarket-Data-Analysis.git
   ```

2. **Open the Jupyter Notebook**

   Launch Jupyter Notebook and open the data wrangling notebook:

   ```
   jupyter notebook
   ```

   In the Jupyter Notebook interface, navigate to the `Notebooks` folder and open `Data_Wrangling.ipynb`.

3. **Open the Power BI Report**

   To explore interactive visualizations, open the Power BI report:

   1. Open **Power BI Desktop**.
   2. Load the file `Paginated_Report.pbix`.

## Results and Insights

This project provides a robust analysis of supermarket sales data, offering several valuable insights:

- **Branch and City Performance:** Identifies top-performing branches and cities based on sales volume and revenue.
- **Customer Segmentation:** Analyzes purchasing patterns across different customer demographics.
- **Product Line Profitability:** Assesses product line performance to guide inventory and marketing strategies.
- **Payment Methods:** Evaluates payment method preferences to optimize the checkout process.
