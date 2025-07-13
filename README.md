📁 Initial Data Exploration & Imputation – Pakistan E-Commerce Dataset
=
📌 **Project Overview**

This notebook focuses on preliminary data exploration and cleaning for a real-world e-commerce dataset from Pakistan.
The goal is to prepare the dataset for further analysis by identifying structural issues, sanitizing column names, and addressing invalid or missing values.

🧹 **Data Cleaning Highlights**

1.Renamed and normalized column headers (lowercase, no whitespace, underscores).

2.Detected missing and placeholder values.

3.Smart, domain-aware imputation of missing categories using SKU-based mapping:

Instead of relying on generic fillers (like "Unknown" or the mode), the notebook uses a predefined SKU-to-Category mapping to intelligently populate missing values in category_name_1.
This preserves semantic accuracy and reflects real business logic.

**This project is intended as a foundational step in building good habits around clean, interpretable datasets — with emphasis on semantic integrity and structured thinking.**
------------------------------------------------
**For more advanced data cleaning, feature engineering, and full-scale EDA with rich visualizations and modeling,
see my Olympic Weightlifting Analysis Project – where I apply techniques like:** 
* Data enrichment via the Wikipedia API
* Country normalization using pycountry
* Regex-based text standardization + Imputation based on external reference datasets
