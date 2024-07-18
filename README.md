# Credit Card Financial Dashboard

## Project Overview
The objective of this project is to develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends. This dashboard enables stakeholders to monitor and analyze credit card operations effectively, facilitating data-driven decision-making.

## Table of Contents
- [Introduction](#introduction)
- [Project Objective](#project-objective)
- [Data](#data)
- [Methodology](#methodology)
- [Dashboard Insights](#dashboard-insights)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
Credit card companies need to track various metrics to understand their performance and customer behavior. This project leverages data from SQL databases, processes it using DAX queries, and visualizes it through an interactive Power BI dashboard. The dashboard offers insights into revenue, transactions, customer demographics, and other critical metrics.

## Project Objective
To develop a credit card financial dashboard that provides:
- Real-time insights into key performance metrics.
- Trends analysis to monitor credit card operations effectively.
- Actionable insights to support stakeholders in decision-making.

## Data
The data used in this project includes:
- **Customer Details**: Demographic information of credit card users.
- **Credit Card Transactions**: Details of transactions made using credit cards.
- **Financial Metrics**: Revenue, transaction amounts, interest earned, etc.

The data is processed and stored in SQL databases. DAX queries are used for data processing within Power BI to derive meaningful insights.

## Methodology
1. **Data Download**: Obtain the data from [GitHub](https://github.com/Jar-Tima/Credit_Card_Financial_Dashboard).
2. **SQL Database Preparation**:
    - Prepare CSV files.
    - Create tables in SQL.
    - Import CSV files into SQL.
3. **DAX Queries**:
    - Define age and income groups.
    - Calculate weekly revenue and other financial metrics.
4. **Power BI Dashboard**:
    - Create visualizations to display insights.
    - Monitor key performance metrics and trends.

## Dashboard Insights
- **Weekly Overview**:
    - Revenue increased by 28.8% in Week 53.
    - Total transaction amount and count increased.
    - Customer count increased.
- **Year-to-Date (YTD) Overview**:
    - Overall revenue: $57M
    - Total interest: $8M
    - Total transaction amount: $46M
    - Male customers contributed more to revenue: $31M (Male) vs. $26M (Female)
    - Blue & Silver credit cards accounted for 93% of transactions.
    - TX, NY & CA contributed 68% to overall transactions.
    - Activation rate: 57.5%
    - Delinquency rate: 6.06%

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Credit_Card_Financial_Dashboard.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Credit_Card_Financial_Dashboard
    ```
3. Set up the SQL database and import data using the provided SQL scripts.

## Usage
To use the dashboard, follow these steps:
1. Import the SQL data into Power BI.
2. Execute the DAX queries to process the data.
3. Visualize the data using Power BI to generate the dashboard.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss any changes or improvements.
