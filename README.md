# 📊 Swiggy Financial Correlation Analysis

## Business Analytics Project

Analyzing relationships among key financial variables of Swiggy using correlation analysis and heatmap visualization.

## Executive Summary

Financial statements contain numerous interconnected variables that influence business performance.

This project applies correlation analysis and heatmap visualization techniques to Swiggy's balance sheet data to identify relationships among financial indicators and gain deeper insights into the company's financial structure.

The project demonstrates the practical application of Python-based business analytics techniques in financial analysis and decision-making.

## Business Context

Swiggy is one of India's leading food delivery and quick-commerce platforms.

Understanding relationships between financial statement variables can help analysts identify patterns in capital allocation, liabilities, investments, and asset growth.

This project explores these relationships using correlation analysis to uncover meaningful financial insights.

## Objectives

- Analyze Swiggy's financial statement data
- Calculate correlation coefficients among financial variables
- Visualize relationships using heatmaps
- Identify strong positive and negative relationships
- Derive business insights from financial patterns

## Dataset

Source:
Financial statement data extracted from Screener using publicly available Swiggy balance sheet information.

The dataset contains variables including:

- Equity Capital
- Reserves
- Borrowings
- Other Liabilities
- Total Liabilities
- Investments
- Other Assets
- Total Assets

and other balance sheet indicators across multiple years.

## Tools & Technologies

| Tool | Purpose |
|--------|--------|
| Python | Data Analysis |
| Pandas | Data Processing |
| Seaborn | Heatmap Visualization |
| Matplotlib | Data Visualization |

## Methodology

### Step 1: Data Collection

Collected Swiggy financial statement data from Screener.

### Step 2: Data Preparation

Imported and prepared the dataset using Pandas.

### Step 3: Correlation Analysis

Generated a correlation matrix to identify relationships among variables.

### Step 4: Visualization

Created a heatmap using Seaborn to visually interpret the relationships.

### Step 5: Interpretation

Analyzed the correlation patterns and extracted business insights.

## Core Analysis

```python
corr = df.corr(numeric_only=True).round(2)

sns.heatmap(
    corr,
    annot=True,
    cmap="coolwarm",
    square=True
)
```

## Results

### Correlation Heatmap

![Heatmap](images/heatmap.png)

## Key Findings

- Several financial variables demonstrate strong positive relationships.
- Asset-related indicators exhibit interconnected growth patterns.
- The heatmap effectively highlights financial dependencies across balance sheet components.
- Correlation analysis provides a quick way to identify patterns hidden in raw financial data.

## Business Relevance

Correlation analysis helps organizations:

- Understand relationships among financial indicators
- Identify performance drivers
- Support strategic decision-making
- Detect financial patterns and dependencies

This project demonstrates how analytics can convert raw financial statements into meaningful business insights.

## Learning Outcomes

Through this project, I strengthened my understanding of:

- Business Analytics
- Financial Data Analysis
- Correlation Analysis
- Data Visualization
- Python for Business Applications

This project reflects my growing interest in using data-driven approaches to understand business performance and support decision-making.

## Author

Mridul Krishna Parauha

BBA (Digital Marketing & AI) Student

Passionate about Business Analytics, Marketing, AI, and Data-Driven Decision Making.
