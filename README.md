# Exploratory Data Analysis and Statistical Inference with the Boston Housing Dataset

This project uses historical Boston-area housing data to demonstrate exploratory data analysis and statistical inference in Python. It combines descriptive statistics, data visualization, interval estimation, and hypothesis testing.

## Dataset

The dataset contains 506 Boston-area census tracts and 14 housing, demographic, and spatial variables. The CSV file is available in the `data` directory.

> **Data ethics note:** The B variable is a nonlinear and historically controversial transformation related to racial composition. It is interpreted only as a transformed indicator and not as a direct measure of the proportion of Black residents.

## Methods

- Descriptive statistics and distribution analysis
- Covariance analysis
- Pearson correlation analysis
- Confidence interval for a population mean
- Confidence interval for a population proportion
- Confidence interval for a population standard deviation
- Comparison of 90%, 95%, and 99% confidence intervals
- Independent two-sample hypothesis testing
- Statistical visualization with Matplotlib and Seaborn

## Key findings

- CRIM and LSTAT have a moderate positive correlation.
- AGE and DIS have a strong negative correlation.
- The mean AGE value is approximately 68.57%, with a 95% confidence interval of 66.12–71.03%.
- Approximately 6.92% of the examined census tracts border the Charles River.
- The sample standard deviation of MEDV is approximately $9,197.
- The two-sample test found no statistically significant difference in mean B between census tracts bordering and not bordering the Charles River.

## Repository structure

- `boston_housing_statistical_inference.ipynb` – complete analysis
- `data/boston_housing.csv` – dataset
- `data/README.md` – dataset description
- `requirements.txt` – required Python packages

## Running the project

1. Download or clone the repository.
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
