🧹 Data Cleaning Project using JupyterLite
📌 Project Title

Data Cleaning and Preprocessing of Airbnb NYC Dataset

📖 Project Description

Data cleaning is a crucial step in data analysis that involves identifying and fixing incorrect, incomplete, duplicate, or inconsistent data.
In this project, the Airbnb NYC 2019 dataset (AB_NYC_2019.csv) is cleaned using JupyterLite, a browser-based Python environment.

The goal of this project is to improve data quality and reliability so that the dataset can be used for accurate analysis and decision-making.

🛠️ Tools & Technologies Used

JupyterLite (Browser-based Python environment)

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib – Data visualization

⚠️ Note: seaborn is not supported in JupyterLite and hence not used.

📂 Dataset Information

Dataset Name: Airbnb NYC 2019

File: AB_NYC_2019.csv

Source: Public Airbnb dataset

Records: Listings of Airbnb properties in New York City

Attributes: Price, location, room type, reviews, availability, etc.

🔑 Key Concepts Implemented

Data Integrity – Ensured accuracy and consistency of data

Missing Data Handling – Filled missing values logically

Duplicate Removal – Removed duplicate records

Standardization – Unified text formatting and removed invalid values

Outlier Detection – Identified and removed extreme values using IQR method

⚙️ Project Workflow

Upload dataset to JupyterLite

Load CSV file using Pandas

Explore dataset structure and statistics

Handle missing values

Remove duplicate records

Standardize categorical data

Detect and remove outliers

Save cleaned dataset

📊 Outlier Detection Method

Technique Used: Interquartile Range (IQR)

Visualization: Matplotlib Box Plot

Reason: Prevent skewed analysis caused by extreme price values

📁 Output Files

Cleaned Dataset: Cleaned_AB_NYC_2019.csv

▶️ How to Run the Project

Open JupyterLite

Upload AB_NYC_2019.csv

Open the notebook

Run cells step-by-step

Download Cleaned_AB_NYC_2019.csv from file explorer

📝 Conclusion

This project demonstrates essential data cleaning techniques using a browser-based Python environment.
After cleaning, the dataset becomes more reliable and suitable for data analysis and machine learning tasks.
