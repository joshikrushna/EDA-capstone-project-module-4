tablu link :- https://public.tableau.com/views/krushnajoshiHMAEDA/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
# EDA-capstone-project-module-4
Hotel Booking Analysis Dashboard

Project Overview

This project provides an in-depth analysis of hotel booking data from two types of hotels: City Hotel and Resort Hotel. The dataset consists of 119,390 rows and 32 columns. The goal of this project is to gain actionable insights into hotel booking patterns, cancellations, and revenue generation using Data Manipulation, Data Cleaning, and Exploratory Data Analysis (EDA)
Table of Contents

Project Overview

Data Collection

Data Cleaning

Data Visualization

Insights and Analysis

Dashboard Features

Technologies Used

Setup Instructions

Conclusion

Contact
Data Collection

Utilized functions like head(), tail(), describe(), info() to understand the dataset.

Identified columns with missing or redundant data.

Dropped duplicate columns to ensure data accuracy.

Data Cleaning

Removed duplicate rows using drop_duplicates(), reducing the data from 119,390 rows to 87,396 rows.

Applied data wrangling techniques to handle missing values.

Columns with excessive null values were dropped using drop().

Columns with minimal null values were imputed using .fillna() with appropriate values.

Data Visualization

Visualizations were created to represent the relationships between variables using various plotting techniques:

Pie Charts: Visualized categorical data distributions.

Histograms: Showed booking frequency.

Bar Charts: Compared revenues and market segments.

Scatter Plots: Analyzed night stays and booking patterns.

Heatmaps: Displayed correlation among variables using seaborn.

Pair Plots: Demonstrated relationships between different columns with a focus on children-related data.

Line Charts: Depicted booking trends by week and month.

Cancellation Analysis: Visualized canceled vs. non-canceled bookings.

Insights and Analysis

Identified booking patterns for different hotel types.

Analyzed seasonal and monthly trends to understand peak booking periods.

Evaluated market segments to identify high-revenue sources.

Examined cancellation trends for effective business strategies.

Provided actionable insights using visual storytelling.

Dashboard Features

Interactive Filters: Enable users to explore data by hotel type, month, or booking status.

Dynamic Visuals: Seamless visualization updates based on user selections.

User-Friendly Layout: Clear navigation with well-structured charts.

Responsive Design: Adaptable across devices.

Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook

Tableau (for Dashboard Visualization)





Open the Tableau file to view the interactive dashboard.

Conclusion

This project provides a comprehensive view of hotel booking behaviors, empowering stakeholders to make data-driven decisions. The insights can be used to optimize pricing strategies, manage inventory, and reduce cancellations.

Contact

For any inquiries or feedback, feel free to reach out:

GitHub: krushnajoshi

Email: Krishnajoshi1258@gmail.com
