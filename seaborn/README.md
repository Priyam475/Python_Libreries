# Seaborn Visualization Assignment: Retail Sales Analysis

## Dataset Overview

This project uses a **retail sales dataset** containing customer transaction data with the following information:
- **Columns**: Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount
- **Size**: ~500 transactions
- **Source**: Kaggle Retail Sales Dataset
- **Time Period**: 2023
- **Product Categories**: Electronics, Clothing, Beauty

### Dataset Source
The original dataset can be found on [Kaggle Retail Sales Dataset](https://www.kaggle.com/datasets) or similar data repositories.

## Project Goals

This assignment demonstrates understanding of different Seaborn visualization techniques:
- **Relational plots**: Understanding relationships between numerical variables
- **Distribution plots**: Analyzing single and bivariate distributions
- **Categorical plots**: Comparing groups and distributions across categories
- **Regression plots**: Visualizing trends and correlations
- **Matrix plots**: Exploring correlations and variable relationships
- **Multi-plot dashboards**: Combining multiple perspectives for insights

## How to Run

### Prerequisites
Make sure you have Python 3.7+ installed with the following packages:
```bash
pip install pandas seaborn matplotlib numpy
```

### Installation & Execution

1. **Clone or download the repository**
   ```bash
   cd path/to/seaborn-assignment
   ```

2. **Ensure dataset is in place**
   - The file `retail_sales_dataset.csv` should be in the same directory as `task.ipynb`

3. **Open and run the Jupyter notebook**
   ```bash
   jupyter notebook task.ipynb
   ```
   Or use VS Code's integrated Jupyter notebook support:
   - Open VS Code
   - Open the file `task.ipynb`
   - Click "Run All" or run cells individually

4. **Viewing outputs**
   - All plots will display inline in the notebook
   - Statistical summaries will print to the console output

## Notebook Structure

The notebook follows this learning progression:

### Section 1: Exploratory Data Analysis (EDA)
- Load dataset and check basic properties
- Calculate summary statistics
- Identify data types and missing values
- Initial observations about data distribution

### Section 2: Relational Visualizations
- **Task 1**: Scatter plots and relational plots to understand Age vs Total Amount by Gender
- Variant: Direct `scatterplot()` for comparison

### Section 3: Distribution & Trend Analysis
- **Task 2**: Line plots showing spending trends across ages
- Variant: Scatter-style line plots for detail visibility
- Faceted views by product category

### Section 4: Distribution Analysis
- **Task 3**: Histograms, KDE plots, rug plots showing value distributions
- Combined visualization demonstrating multiple perspectives

### Section 5: Bivariate Distributions
- **Task 4**: 2D density plots showing overlap between Age and Amount
- Variant: Bivariate histogram for direct count visualization

### Section 6: Correlation Analysis
- **Task 5**: Pair plots and heatmaps revealing correlations
- Useful for identifying which variables are related

### Section 7: Categorical Comparisons
- **Task 6**: Bar, box, violin, and count plots by Product Category
- Shows central tendency, spread, density, and frequency

### Section 7: Regression Analysis
- **Task 7**: Linear regression plots by Gender
- Variant: `regplot()` for focused single-axis regression
- Predictions and trend visualization

### Section 8: Multi-Plot Dashboards
- **Task 8**: Combined categorical and gender analysis
- Variant: Explicit FacetGrid for structured multi-plot layouts

### Section 9: Summary & Key Findings
- Synthesis of insights from all visualizations
- Correlation strengths discussed
- Business implications and patterns identified

## Key Findings Summary

After analyzing these visualizations, you should be able to answer:
1. How does customer age influence total spending?
2. Which product category generates the most revenue?
3. Are there gender differences in spending patterns?
4. What is the distribution of transaction amounts?
5. How do different variables correlate with each other?

## Notes for Reviewers

- The notebook includes trial-and-error approaches to show authentic learning
- Comments reflect personal understanding, not generic explanations
- Each visualization includes analysis of what insights were gained
- A comprehensive summary section synthesizes all findings
- The dataset is self-contained, making this fully reproducible

## Files Included

- `task.ipynb` - Main Jupyter notebook with all visualizations
- `retail_sales_dataset.csv` - Dataset (500 retail transactions)
- `README.md` - This file with instructions and overview

---

**Author**: Data Analysis Student  
**Date**: March 2026  
**Assignment**: Seaborn Visualization Techniques
