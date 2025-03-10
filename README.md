# RFM-Analysis for a Logistics Company

This repository contains the tools, scripts, and documentation for performing RFM (Recency, Frequency, Monetary) analysis specifically tailored for a logistics company. The goal of the project is to segment customers based on their behavior and identify opportunities to optimize customer engagement, retention, and profitability.
![dashboard](https://github.com/user-attachments/assets/57747b27-8d4b-4664-96a8-a167c228cb0a)

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Data Requirements](#data-requirements)
- [RFM Methodology](#rfm-methodology)
- [Results](#results)
- [Segmentation Strategies](#segmentation-strategies)

---

## Introduction

RFM analysis is a powerful customer segmentation technique that helps businesses classify their customers based on the following parameters:

- **Recency**: How recently a customer made a transaction.
- **Frequency**: How often a customer makes transactions.
- **Monetary**: How much revenue the customer generates.

This project applies RFM analysis to logistics company data, focusing on:

- Identifying high-value customers.
- Analyzing customer activity trends.
- Supporting targeted marketing campaigns.

---

## Features

- Data preprocessing and cleansing.
- Automated RFM score computation.
- Customizable thresholds for RFM segmentation.
- Visualization of customer segments and trends.
- Actionable insights to improve customer engagement.


---

## Data Requirements

The dataset should include the following columns:

| Column Name          | Description                             |
|----------------------|-----------------------------------------|
| date                 | Date and time of the transaction.      |
| client               | Name or identifier of the client.      |
| transportation_mode  | Mode of transportation (e.g., SEA, AIR, ROAD, RAIL). |
| revenue_usd          | Revenue generated in USD.              |
| cost_usd             | Cost incurred in USD.                  |
| profit_usd           | Profit generated in USD.               |
| margin_percent       | Profit margin percentage.              |

Ensure the data is in CSV format and cleaned of duplicates or missing values.

---

## RFM Methodology

1. **Data Preprocessing**: Clean and format raw data for analysis.
2. **Score Calculation**:
   - Assign scores (1-5) for each RFM metric based on thresholds derived from quantiles.
   - Combine scores to form a composite RFM score.
3. **Segmentation**:
   - Group customers into segments (e.g., Champions, Loyal, At-Risk) based on RFM scores.
4. **Visualization**: Generate plots to visualize segments and trends.

---

## Results

- **Insights**: Identify key customer groups driving revenue.
- **Reports**: Detailed visualizations for stakeholders.
