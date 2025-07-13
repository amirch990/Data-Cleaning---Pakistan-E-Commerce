📁 Initial Data Exploration – Pakistan E-Commerce Dataset

📌 Project Overview

This notebook focuses on preliminary data exploration and cleaning for a real-world e-commerce dataset from Pakistan.
The goal is to prepare the dataset for further analysis by identifying structural issues, sanitizing column names, and addressing invalid or missing values.

🧹 Data Cleaning Highlights

1.Renamed and normalized column headers (lowercase, no whitespace, underscores).

2.Detected missing and placeholder values.

3.Smart, domain-aware imputation of missing categories using SKU-based mapping:

Instead of relying on generic fillers (like "Unknown" or the mode), the notebook uses a predefined SKU-to-Category mapping to intelligently populate missing values in category_name_1.
This preserves semantic accuracy and reflects real business logic.
