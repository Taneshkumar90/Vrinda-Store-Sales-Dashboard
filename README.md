# Vrinda-Store-Sales-Dashboard
Virinda's sales store analysis

## Project Overview
This project involves an end-to-end data analysis of Vrinda Store, a fashion retail business. The goal was to analyze sales data to identify key performance indicators (KPIs) and provide actionable insights to help the store grow its sales in 2023. The final output is an interactive Excel dashboard that visualizes sales trends, customer behavior, and regional performance.

Objective
Vrinda Store needed a comprehensive Annual Sales Report to understand their customers better and identify growth opportunities for the coming year. The primary business questions addressed were:

- Which month achieved the highest sales and orders?

- Who purchases more—Men or Women?

- What are the different order statuses (delivered, returned, etc.)?

- Which are the top 5 states contributing to sales?

- What is the relation between age and gender in purchasing behavior?

- Which sales channel (Amazon, Flipkart, Myntra, etc.) contributes the most?


### Tools & Technologies Used
Microsoft Excel (Primary Tool)

### Process
#### 1. Data Cleaning
- Checked for missing/null values in the dataset.

- Standardized data entries (e.g., replaced 'M' with 'Men', 'W' with 'Women').

- Corrected values in the 'Qty' column (converting "One", "Two" to numeric 1, 2).

#### 2. Data Processing
- Age Grouping: Created a new column to categorize customers into Teenager, Adult, and Senior using logical formulas.

- Month Extraction: Extracted month names from the 'Date' column to perform monthly trend analysis.

#### 3. Data Analysis & Visualization
Key metrics were analyzed using Pivot Tables and visualized with the following charts:

- Orders vs. Sales: Combo Chart (Columns for Sales, Line for Order Count).

- Men vs. Women Sales: Pie Chart.

- Order Status: Pie Chart showing the percentage of delivered vs. returned orders.

- Top 5 States: Horizontal Bar Chart.

- Age & Gender Relation: Clustered Column Chart.

- Sales by Channel: Bar Chart/Pie Chart.

#### 4. Interactive Dashboard
Consolidated all charts into a single Dashboard sheet.

Added Slicers for Month, Channel, and Category to make the dashboard dynamic and interactive.

- Data Cleaning: Check for null values, find & replace (standardizing gender values 'M' to 'Men'), data type formatting.

- Data Processing: Creating new columns for Age Group (using IF formula) and Month (using TEXT formula).

- Data Analysis: Pivot Tables and Pivot Charts.

- Visualization: Interactive Dashboard with Slicers.
