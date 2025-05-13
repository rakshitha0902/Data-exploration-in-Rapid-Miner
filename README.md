Renewable Energy and Electricity Demand Analysis
This repository contains the dataset, RapidMiner project file, and a comprehensive report for analyzing electricity demand and renewable energy generation trends across England and Wales, using data from 2009 to 2024. The analysis explores the relationship between electricity demand, renewable energy generation (wind and solar), and energy flows between regions. Additionally, it includes advanced analysis, prediction models, and key findings based on the data.

Repository Contents
Dataset: A dataset containing hourly data on electricity demand and renewable energy generation, spanning from 2009 to 2024. The dataset includes key attributes such as Demand_England_Wales, Wind_Generation, Solar_Generation, and interconnector flows with neighboring countries.

RapidMiner File: A RapidMiner project file that includes the data exploration, feature engineering, and model comparisons (Decision Tree, Random Forest, and Gradient Boosting) for predicting electricity demand or renewable energy generation.

Report: The full report detailing the dataset, methodology, analysis, findings, and model evaluation results. The report also includes visualizations and insights on trends, correlations, and interdependencies between electricity demand and renewable generation.

How to Use
Download the Dataset: Access the dataset from the data folder in this repository.

Open the RapidMiner File: Use RapidMiner to load the dataset, perform exploratory data analysis (EDA), and run the models. The project file includes all necessary steps.

Generate Insights: The report provides an in-depth explanation of the analysis, including insights from both exploratory and advanced analyses.

Key Findings
Hourly Demand Trends: Demand patterns peak during working hours and dip at night.

Seasonal Renewable Generation: Wind generation peaks in winter, while solar generation peaks in summer, suggesting a complementary renewable energy mix.

Demand and Generation Correlation: Wind and solar generation do not always align with peak demand, requiring storage solutions.

Cross-Border Electricity Flow: France and the Netherlands are the major contributors to electricity imports, with France showing consistent supply patterns.

Models Used
Decision Tree: A simple model for predicting electricity demand, showing strong alignment with actual values.

Random Forest: Less accurate for this dataset, with higher errors compared to Decision Tree and Gradient Boosting.

Gradient Boosting: The best-performing model, offering high accuracy and close correlation with actual data.

Requirements
RapidMiner: The project was developed using RapidMiner Studio. Download the latest version of RapidMiner to open and run the file.

Libraries: Ensure necessary libraries and extensions for data processing and model building are installed in RapidMiner.
