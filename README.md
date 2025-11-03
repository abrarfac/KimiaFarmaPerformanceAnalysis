# KimiaFarmaPerformanceAnalysis
this project focuses on evaluating business performance from 2020 to 2023. In-depth analysis of operational and financial data is crucial to identify trends and support data-driven decision-making. The data used includes transaction details, products, inventory, and branch office information sourced from CSV files that were imported into BigQuery.

The main challenge of this project is transforming the scattered raw data into an integrated and interactive analytical dashboard in Google Looker Studio, using datasets imported from Google BigQuery that have been processed using SQL queries. This dashboard aims to monitor overall business performance covering aspects of sales, profitability, branch performance, and customer satisfaction, to provide insights that are easy to understand and actionable for Kimia Farma’s future strategic planning.

Project Stages:

Importing Datasets to BigQuery: Four main datasets provided (kf_final_transaction.csv, kf_product.csv, kf_inventory.csv, kf_kantor_cabang.csv) were imported into Google BigQuery. This data was placed in a special dataset for Kimia Farma.
Creating Analysis Tables: We created a main analysis table named analisa_dashboard_kimia_farma by combining the four source tables using BigQuery SQL. This table also includes calculations of key metrics such as nett_sales and nett_profit, which are very important for analysis.
Dashboard Creation in Looker Studio: Based on the analysis table that has been created, an interactive dashboard is designed in Google Looker Studio to visualize performance data.

Dataset: This project uses the following datasets:

kf_final_transaction: Contains sales transaction details.
kf_product: Contains product information.
kf_inventory: Contains product inventory data at branches.
kf_kantor_cabang: Contains branch location and rating information.

kf_inventory: Contains product inventory data at branches.

kf_kantor_cabang: Contains branch location and rating information.
