🌍 Renewable Energy and Electricity Demand Analysis
This repository contains an in-depth analysis of electricity demand patterns and renewable energy generation trends using publicly available data from 2009 to 2024. The project focuses on exploring relationships between electricity demand, wind and solar generation, and energy flows across regions in the UK, particularly in England and Wales. The repository includes the dataset, RapidMiner project file, and report summarizing the findings.

📁 Repository Contents
historic_demand_2009_2024_noNaN.xlsx – The cleaned dataset containing hourly data on electricity demand, renewable energy generation (wind and solar), and energy flows between regions.

DA_Process.rmp – The RapidMiner project file used to analyze the dataset, perform exploratory data analysis (EDA), and run prediction models.

Data_Analytics.docx – The detailed report summarizing key findings, visualizations, and analysis results.

README.md – This file.

📌 Project Overview
The goal of this project is to explore electricity demand and renewable energy generation patterns in the UK, and assess how well wind and solar power can meet demand, particularly during peak times. The dataset spans from 2009 to 2024 and includes data on electricity use, wind generation, solar generation, and cross-border energy flows.

🛠️ Key Steps Performed
Data Exploration: Investigated key demand and generation attributes, including Demand_England_Wales, Wind_Generation, and Solar_Generation.

Feature Engineering: Added new features such as seasonal trends, demand and generation correlations, and interconnector flows.

Modeling: Evaluated multiple prediction models (Decision Tree, Random Forest, Gradient Boosting) to forecast electricity demand.

Visualization: Created graphs such as hourly demand trends, seasonal renewable generation, and cross-border energy flows to explore patterns and dependencies.

📈 Main Insights
Hourly Demand Trends: Peak electricity demand occurs during working hours (10 AM to 7 PM), while demand decreases in the late evening.

Seasonal Renewable Generation: Wind generation peaks in winter, while solar generation is highest in summer, complementing each other to balance demand.

Demand vs. Renewable Generation: Renewable generation does not fully match peak demand times, indicating a need for energy storage solutions.

Electricity Flow Across Borders: France and the Netherlands play significant roles in supplying electricity, with variations based on domestic demand and policy changes.

🧰 Tools Used
RapidMiner for data processing, EDA, and model building

Microsoft Word for report generation

Markdown for documentation and reproducibility

📑 How to Run
Download the Dataset: Access the dataset from the historic_demand_2009_2024_noNaN.xlsx file in this repository.

Open the RapidMiner File: Open the DA_Process.rmp project in RapidMiner to run the analysis and generate the models.

Review the Report: The Data_Analytics.docx contains detailed analysis, visualizations, and model evaluation results.
