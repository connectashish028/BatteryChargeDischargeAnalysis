# Data-Driven Battery Performance Analysis

This repository contains a Jupyter Notebook that performs a comprehensive analysis of two battery types: KOKAM SLPB 526495 Pouch Cell and LG Chem INR21700 M5018.20. The analysis leverages data analysis, visualization, and machine learning techniques to gain insights into battery performance and predict capacity.

## Project Overview

The primary objectives of this project are:

- **Understand Battery Behavior:** Investigate the charging and discharging characteristics of both battery types, including voltage, current, and capacity trends over time.
- **Compare Battery Performance:** Analyze and compare the performance of Kokam and LG Chem batteries in terms of efficiency, capacity retention, and other key metrics.
- **Build Predictive Models:** Develop machine learning models to accurately predict battery capacity based on observed data, such as time, voltage, current, power, and charge cycles.

## Dataset

The analysis is based on two datasets:

- **KOKAM SLPB 526495:** Data is sourced from an Excel file (`kokum_data.xlsx`) containing time-series measurements of voltage, current, power, charge cycles, and accumulated charge/discharge (Ah).
- **LG Chem INR21700 M5018.20:** Similar data is obtained from an Excel file (`LG_data.xlsx`) for the LG Chem battery.

## Analysis and Visualization

The Jupyter Notebook performs the following analysis and visualization:

- **Exploratory Data Analysis:** Summary statistics, correlation analysis, and data cleaning are performed to understand the datasets.
- **Time-Series Plots:** Visualize voltage, current, power consumption, and accumulated charge/discharge over time.
- **Scatter Plots:** Explore relationships between variables like voltage and power.
- **Hysteresis Loops:** Visualize the relationship between capacity and voltage.
- **Correlation Heatmaps:** Identify correlations between different variables.

## Predictive Modeling

The notebook utilizes machine learning models to predict battery capacity:

- **Feature Selection:** Relevant features are selected for capacity prediction.
- **Model Training and Evaluation:** Models like Linear Regression, Random Forest, Gradient Boosting, Support Vector Regressor, and K-Nearest Neighbors are trained and evaluated using MAE and MSE.
- **Cross-Validation:** Assesses model generalization and robustness.
- **Feature Importance:** Identifies key drivers of battery capacity.

## Results

- **Model Performance:** Both Random Forest and K-Nearest Neighbors demonstrate superior performance in predicting battery capacity, achieving very low MAE and MSE on the test set.
- **Actionable Insights:** The analysis provides valuable insights into the performance characteristics of both battery types, which can be used to optimize battery management strategies.

## Getting Started

To run the analysis, follow these steps:

1. Clone this repository.
2. Open the Jupyter Notebook (`Battery_Performance_Analysis.ipynb`) in Google Colab or a compatible environment.
3. Install the required libraries (pandas, numpy, matplotlib, seaborn, plotly, scikit-learn).
4. Execute the notebook cells to perform the analysis and generate visualizations.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

