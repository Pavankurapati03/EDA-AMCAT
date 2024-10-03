# Exploratory Data Analysis on AMCAT

## Project Overview

This project involves performing Exploratory Data Analysis (EDA) on a dataset related to salary outcomes for engineering graduates. The objective is to analyze the data, find trends and patterns, and test hypotheses about employment outcomes using various data visualization and analysis techniques. The target variable for the analysis is **Salary**.

## Dataset Information

- **Dataset:** Aspiring Mind Employment Outcome 2015 (AMEO) Study
- **Size:** ~4000 data points
- **Features:** Around 40 independent variables, covering cognitive skills, technical skills, personality traits, and demographic information.

## Project Structure

1. **Introduction:**  
   The objective and dataset description are provided in this section. The primary goal is to understand the factors influencing salary and employment outcomes for engineering graduates.

2. **Data Import and Overview:**
   - Load the dataset using Python libraries (Pandas, NumPy).
   - Display the dataset's structure (head, shape, and description).

3. **Univariate Analysis:**
   - Visualized each variable independently.
   - Plots include histograms, boxplots, countplots, and probability density functions (PDFs) for numerical and categorical columns.
   - Identified outliers and observed distributions in the data.

4. **Bivariate Analysis:**
   - Relationships between numerical variables using scatter plots, pair plots, and correlation matrices.
   - Explored patterns between categorical and numerical variables using boxplots, barplots, and swarm plots.
   - Identified relationships between categorical variables using stacked bar plots.

5. **Research Questions:**
   - Tested the hypothesis: *Fresh graduates with a Computer Science background can earn up to 2.5-3 lakhs as a starting salary.*
   - Investigated whether **gender** influences the choice of **specialization** among graduates.

6. **Conclusions:**
   - Key findings from the analysis were summarized, including insights into factors affecting salary outcomes.

7. **Bonus Insights (Optional):**
   - Additional research questions or unique trends identified during the analysis.

## Requirements

- Python 3.x
- Libraries: 
  - Pandas
  - NumPy
  - Seaborn
  - Matplotlib
  - Plotly
  - SciPy

## How to Run

1. Install the necessary libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib plotly scipy
   ```
2. Open the Jupyter Notebook file (.ipynb) and run the cells in order to reproduce the analysis.
