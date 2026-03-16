# Lost_revenue_data_analysis_project
This data analysis project investigates potential revenue loss within the operations of ASOS plc, a global online fashion retailer that sells products from more than 850 brands and serves customers worldwide.

Overview

This project demonstrates a practical data analysis workflow. The notebook (ColabProject1.ipynb) shows how to load the dataset, inspect and clean it, extract quick insights, and produce a brief business recommendation based on the findings.

Dataset
Filename: products_asos.csv (included / uploaded to the Colab environment)
Shape: 30,845 rows × 9 columns
Sample columns: url, name, size, category, price, color, sku, description, images

Tools & Environment
Google Colab (Python 3)
Core libraries: pandas, matplotlib, seaborn
Notebook included: ColabProject1.ipynb

How to run
Upload products_asos.csv to Colab or mount Google Drive and place the file in the working directory.
Open ColabProject1.ipynb in Google Colab.
Run cells sequentially:
Data loading cell: check path to products_asos.csv
EDA cells: df.head(), df.info(), df.describe(), plots
Cleaning cells: handling missing values, removing duplicates, dtype fixes
Results cells: summary stats and the business recommendation cell
