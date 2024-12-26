# Gross National Income (Per Capita) vs Social Indicators: A Regression Analysis

This repository contains the analysis of the relationship between Gross National Income (GNI) per capita and various social indicators. The project aims to explore the limitations of GDP as a welfare indicator and assess whether aggregate economic measures adequately capture societal well-being.

## Project Overview

The study utilizes data from the World Bank and other sources to analyze the interplay between economic metrics and social indices such as the Human Development Index (HDI) and Gender Development Index (GDI). The analysis includes data cleaning, visualization, statistical modeling, and hypothesis testing.

## Repository Structure

- `hdr.xlsx`: The dataset used for the analysis, containing GNI and social indicator variables.
- `ectrx_pre_final.ipynb`: Jupyter Notebook containing the code and detailed analysis.
- `README.md`: Description of the project and instructions for replication.

## Key Features of the Analysis

1. **Dataset Description**:
   - Detailed information about the variables, units, and sample size.
   - Handling of missing values and data cleaning procedures.

2. **Data Exploration**:
   - Descriptive statistics and visualizations such as box plots and correlation heatmaps.
   - Diagnostics for linearity, heteroscedasticity, and normality.

3. **Modeling**:
   - Regression models with subset selection and diagnostics.
   - Multicollinearity checks using VIF and condition indices.

4. **Hypothesis Testing**:
   - Formal statistical tests for relationships between variables.
   - Comparison of null and unrestricted models using ANOVA.

5. **Influence Analysis**:
   - Identification of outliers and influential points using Cook's Distance and leverage plots.

## Instructions for Replication

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/analysis-project.git
   ```

2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook ectrx_pre_final.ipynb
   ```

4. Review the dataset `hdr.xlsx` for variable descriptions.

## Results and Findings

- Insights into the relationship between GNI and social indices.
- Limitations of GDP as a standalone metric for well-being.
- Recommendations for policymakers based on regression analysis.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with proposed changes or enhancements.
