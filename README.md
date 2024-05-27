
# Car Sales Analysis Project

## Overview
This project aims to design and develop a dynamic and interactive Car Sales Dashboard using Power BI. The dashboard visualizes critical Key Performance Indicators (KPIs) related to our car sales, helping us understand sales performance over time and make data-driven decisions.

## Table of Contents
1. Introduction
2. Problem Statement
3. Dataset and Algorithm
4. Data Preprocessing
5. K-means Clustering
6. Power BI Visualizations
7. Results and Insights
8. How to Run
9. Files in Repository

## Introduction
Our company is a car dealership that sells various car models. To effectively track and analyze our sales performance, we need a comprehensive Car Sales Dashboard in Power BI.

## Problem Statement
### KPI Requirements
The dashboard should provide real-time insights into KPIs related to our sales data, enabling us to make informed decisions, monitor progress, and identify trends and opportunities for growth.

#### Sales Overview
- Year-to-Date (YTD) Total Sales
- Month-to-Date (MTD) Total Sales
- Year-over-Year (YOY) Growth in Total Sales
- Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales

#### Average Price Analysis
- YTD Average Price
- MTD Average Price
- YOY Growth in Average Price
- Difference between YTD Average Price and PTYD Average Price

#### Cars Sold Metrics
- YTD Cars Sold
- MTD Cars Sold
- YOY Growth in Cars Sold
- Difference between YTD Cars Sold and PTYD Cars Sold

### Charts Requirement
- YTD Sales Weekly Trend (Line Chart)
- YTD Total Sales by Body Style (Pie Chart)
- YTD Total Sales by Color (Pie Chart)
- YTD Cars Sold by Dealer Region (Map Chart)
- Company-Wise Sales Trend in Grid Form (Tabular Grid)
- Details Grid Showing All Car Sales Information

## Dataset and Algorithm
### Dataset Description
The car sales dataset comprises 23907 records and 16 attributes, capturing essential attributes related to each sale. The dataset provides a comprehensive overview of sales activities over a specified period, allowing for in-depth analysis.

### Mining Algorithm
We employed K-means clustering, a popular unsupervised learning algorithm, to partition the dataset into distinct groups based on similarity.

## Data Preprocessing
1. Handling Missing Values: Identifying and either removing or imputing missing values.
2. Encoding Categorical Variables: Converting categorical variables into numerical format using one-hot encoding.
3. Standardizing Numerical Variables: Scaling numerical variables to a standard scale.

## K-means Clustering
### Implementation Steps
1. Number of Clusters (k): Set based on domain knowledge and techniques like the elbow method.
2. Initialization Method: Common methods include 'random' and 'k-means++'.
3. Convergence Criteria: Defined by a tolerance or maximum number of iterations.

### Validation
The Silhouette Score was used to evaluate the performance of the clustering algorithm, with our model achieving a score of 0.0997.

## Power BI Visualizations
### Dataset Import
The car sales dataset was imported into Power BI using the data import functionality.

### Preprocessing in Power BI
Additional preprocessing steps were performed using Power Query, including cleaning data, handling missing values, and transforming data types.

### DAX Queries
DAX queries were utilized for data manipulation and calculation, creating calculated columns, measures, and tables.

### Visualization Techniques
- Scatter Plots: Visualize relationships between numerical variables.
- Cards: Display KPIs such as total sales and average price.
- Donut Charts: Illustrate the distribution of categorical variables.
- Maps: Show geographic distribution of sales.
- Matrices: Provide a structured view of data for comparison.

## Results and Insights
### Regional Sales Disparities
Identified variations in sales performance across different regions, indicating opportunities for targeted marketing strategies.

### Product Performance Trends
Highlighted changes in sales trends for different product categories, suggesting shifts in consumer preferences and the need for product diversification.

## How to Run
1. Clone the Repository
   ```bash
   git clone https://github.com/yourusername/car-sales-analysis.git
   cd car-sales-analysis
   ```

2. Open the Power BI File
   - Launch Power BI Desktop.
   - Open `Final.pbix`.

3. Run the Jupyter Notebook
   ```bash
   jupyter notebook Power_BI_Final_Project.ipynb
   ```

## Files in Repository
- Car Sales.xlsx: The dataset used for the project.
- Final Presentation.pptx: A presentation detailing the project.
- Final.pbix: The Power BI dashboard file.
- Power_BI_Final_Project.ipynb: The Jupyter notebook for data preprocessing and clustering.
- Problem Statement.docx: Document outlining the problem statements and requirements.

Feel free to explore and contribute to the project! If you have any questions, please open an issue or contact us directly.
