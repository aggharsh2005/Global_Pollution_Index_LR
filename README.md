# Global Pollution Analysis

## Project Overview

This project analyzes the "Global_Pollution_Analysis.csv" dataset to explore various pollution-related metrics across different countries and years. The analysis includes data preprocessing, standardization of pollution indices, encoding of categorical features, and calculation of descriptive statistics for key environmental indicators.

## Dataset

The project uses the `Global_Pollution_Analysis.csv` dataset, which contains the following columns:
* `Country`
* `Year`
* `Air_Pollution_Index`
* `Water_Pollution_Index`
* `Soil_Pollution_Index`
* `Industrial_Waste (in tons)`
* `Energy_Recovered (in GWh)`
* `CO2_Emissions (in MT)`
* `Renewable_Energy (%)`
* `Plastic_Waste_Produced (in tons)`
* `Energy_Consumption_Per_Capita (in MWh)`
* `Population (in millions)`
* `GDP_Per_Capita (in USD)`

## Installation

To run this project, you need to install the required Python libraries. You can do this by running:
pip install -r requirements.txt

How to Run
1.Clone this repository to your local machine.

2.Navigate to the project directory.

3.Install the necessary dependencies as mentioned in the Installation section.

4.Run the main analysis script:
python global_pollution_analysis.py

This will execute the analysis and display the descriptive statistics for CO2 emissions and industrial waste.

## Analysis Details
Data Loading and Cleaning: The dataset is loaded, and any rows with missing values are removed to ensure data quality.

Feature Standardization: The Air_Pollution_Index, Water_Pollution_Index, and Soil_Pollution_Index are standardized using StandardScaler to bring them to a common scale.

Label Encoding: Categorical features like Country and Year are converted into numerical format using LabelEncoder.

Descriptive Statistics: The script calculates and displays key statistical measures (mean, median, mode, min, max, standard deviation) for CO2_Emissions (in MT) and Industrial_Waste (in tons).
