# University Data Mining Project

## Project Overview
This repository contains the collaborative work of our university team focusing on data mining and preprocessing techniques applied to datasets encompassing customer demographic and transactional information. The primary objective was to analyze customer behavior patterns using the Apriori algorithm.

## Project Components

### 1. Data Mining
We used data mining techniques to extract meaningful insights from datasets including:
- `customerAge`
- `customerBuy`
- `customerBuysFrequency`

Our goal was to discover hidden patterns and trends related to customer purchasing behaviors.

### 2. Data Preprocessing
Before applying the Apriori algorithm, we performed data preprocessing steps such as:
- Handling missing values
- Normalizing/transforming data
- Encoding categorical variables
- Structuring the dataset for pattern analysis

The data preprocessing was implemented using **Python**, primarily in **Jupyter Notebooks**.

### 3. Association Rule Mining in WEKA
After preprocessing, we exported the cleaned dataset and used **WEKA** to apply the **Apriori algorithm**.

In WEKA, we:
- Loaded the ARFF/CSV dataset
- Applied the Apriori algorithm
- Analyzed the generated association rules to interpret customer behavior patterns

This step allowed us to efficiently discover frequent itemsets and extract meaningful rules between customer age, purchasing frequency, and product categories.
