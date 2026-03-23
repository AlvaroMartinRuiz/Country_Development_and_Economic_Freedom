# Country Development and Economic Freedom Analysis

![R](https://img.shields.io/badge/Language-R-276DC3?style=for-the-badge&logo=r)
![Markdown](https://img.shields.io/badge/RMarkdown-HTML-orange?style=for-the-badge)

This repository contains an in-depth data analysis project investigating how economic freedom impacts a country's level of development. Development is measured using various socio-economic statistics, such as infant mortality rate, life expectancy, and GDP per capita.

## 📖 Overview
The analysis merges two primary datasets:
1. **WHO Dataset**: Social, economic, health, and political indicators.
2. **Economic Freedom Index (2022)**: Granular economic and freedom metrics per country.

We explore whether the "freest" countries in the world align with those offering the highest quality of life. The notebook extensively covers preprocessing, handling missing values via Random Forest imputation, outlier detection, Principal Component Analysis (PCA), and unsupervised learning techniques such as Clustering.

## 🗂️ Project Structure
- `HWK1_AlvaroMartin.Rmd`: The main R Markdown notebook containing all code, plots, and analysis commentary.
- `HWK1_AlvaroMartin.html`: The compiled HTML report. Open this in any web browser to view the final rendered analysis.
- `WHO.csv` / `index2022_data.csv`: Source datasets used for the analysis.

## ⚙️ Key Methodologies
* **Data Cleaning & Imputation**: Addressed substantial missing values using `mice` (Multiple Imputation by Chained Equations) and Random Forest imputation.
* **Exploratory Data Analysis (EDA)**: Correlation matrices, biometric plots, and geographic assessments of development indicators.
* **Dimensionality Reduction**: Executed PCA to condense 20 variables down to 2 principal components, capturing over 60% of the variance. 
* **Clustering**: Grouping countries into profiles of development to assess the economic baseline of high-income vs. repressed economies.

## 🚀 How to View
The easiest way to view the results is to download or clone this repository and open the `HWK1_AlvaroMartin.html` file in your preferred web browser:

```bash
git clone https://github.com/AlvaroMartinRuiz/Country_Development_and_Economic_Freedom.git
cd Country_Development_and_Economic_Freedom
# Open HWK1_AlvaroMartin.html in your browser
```

To run and compile the code yourself, open `HWK1_AlvaroMartin.Rmd` in RStudio and knit the document. Required libraries will automatically be installed.
