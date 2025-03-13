# Census Data Analysis of USA
Exploratory Data Analysis (EDA) on US Census Data. Investigating income distribution, demographics, and correlations using Python, Pandas, and statistical tests.

## Overview

This project aims at exploratory analysis of US data, with the main objective of identifying trends and related patterns among the distribution of income, in correlation with given demographic data. The dataset contains necessary information on age, employment, education level, marital status, place of birth, hours worked, gender, race, state, and of course, income.

## Dataset

* Census_Data.csv: Raw census data with all the numeric-coded attributes.
* Attribute_Values.csv: Mapping of numeric attribute values to meaningful categories.

## Key Analysis Steps

The project includes the following analyses:

1. Income Distribution Analysis
    * Histogram of income values
    * Log-transformed income distribution
    * Zipf plot and cumulative frequency analysis
2. Demographic Correlations with Work Category
    * Chi-square tests to analyze relationships between gender, race, place of birth, and employment category.
    * Visualization using heatmaps of all the contingencies.
3. Impact and influence of demographic data on income prices
    * Comparisons of average incomes between gender, race and place of birth.
    * T-tests to identify significant differences.
4. Correlations of income with continuous variables
    * Scatter plots for education, age and hours worked in relation to income.
  
Additional statistical tests based on new hypotheses formed from exploratory analysis.

## Technologies Used

* Python
* Pandas for data processing
* Seaborn & Matplotlib for data visualization

## How to Run the Notebook

To execute the analysis, follow these steps:
1. Clone the repository:
   * git clone https://github.com/PolyzosFotios/us-census-data-analysis.git
   * cd us-census-data-analysis
2. Ιnstall the required dependencies:
   * pip install -r requirements.txt
3.	Start Jupyter Notebook:
   * jupyter notebook
4.	Open and run notebook.ipynb.

## License

This project is available under the MIT License.
