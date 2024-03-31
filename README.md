# Correlation_Exercise

This project performs a statistical analysis to estimate the correlation between Income and Age, based on a dataset of 10 observations. The analysis includes calculating Pearson's correlation coefficient and determining the significance of this correlation through a p-value.

## Project Structure

- `Correlation_Exercise.Rmd`: The R Markdown document containing the analysis code, comments, and findings.
- `linregdata.csv`: Dataset used in the analysis, containing three columns: Income (dollars), Age (years), and Education (years).
- `Correlation_Exercise.docs`: The word output of the R Markdown document, presenting the analysis findings.
- `README.md`: This file, provides an overview of the project.

## Data Description

The dataset `linregdata.csv` includes 10 observations with the following variables:
- **Income**: The income of the individual in dollars.
- **Age**: The age of the individual in years.
- **Education**: The years of education of the individual.

## Analysis Summary

The analysis involves calculating Pearson's correlation coefficient (r) to assess the linear relationship between Income and Age. Additionally, a p-value is calculated to test the statistical significance of this correlation.

## Results

- Pearson's correlation coefficient (r): 0.779, indicating a strong positive linear relationship between Income and Age.
- p-value: 0.008, suggesting that the correlation observed is statistically significant and not due to random chance.

## Requirements

This project is implemented in R. To run the analysis, you will need:

- R (version 3.6.0 or later)
- RStudio (optional, but recommended for ease of use)

## How to Run

1. Clone this repository to your local machine.
2. Open `Correlation_Exercise.Rmd` in RStudio or your preferred R environment.
3. Run the Rmd file to reproduce the analysis and view the results.
