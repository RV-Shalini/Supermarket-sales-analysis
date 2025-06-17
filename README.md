# Supermarket Sales Exploratory Data Analysis (EDA)

## Overview
This repository contains an exploratory data analysis (EDA) of a supermarket sales dataset. The analysis uses popular Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to understand data distribution, relationships between variables, and gain insights into sales performance and customer behavior.

---

## Dataset
The dataset used is `supermarket_sales - Sheet1.csv`, containing 1000 rows and 17 columns. Key features include:

- **Invoice ID:** Unique transaction identifier
- **Branch:** Supermarket branch location (A, B, or C)
- **City:** City where the branch is located
- **Customer type:** Member or Normal customer
- **Gender:** Customer gender
- **Product line:** Category of the product sold
- **Unit price:** Price per unit
- **Quantity:** Number of units purchased
- **Tax 5%:** Tax applied on total sale
- **Total:** Total amount including tax
- **Date:** Transaction date
- **Time:** Transaction time
- **Payment:** Mode of payment (Cash, Credit card, Ewallet)
- **COGS:** Cost of goods sold
- **Gross margin percentage:** Gross margin in percentage
- **Gross income:** Gross income earned on the sale
- **Rating:** Customer rating for the purchase experience (out of 10)

---

## Key Steps Performed

1. **Data Loading and Inspection**  
   Loaded the dataset using `pandas.read_csv()`, verified the file path, and previewed the data with `.head()`.

2. **Data Types and Conversion**  
   Checked data types with `.dtypes`. Converted the `Date` column to datetime format for time-based analysis.

3. **Handling Missing Values**  
   Checked for missing values; none were found. Where necessary, missing values in `Unit price` were replaced with the average, and `Quantity` with the mode.

4. **Correlation Analysis**  
   Computed correlation matrix to explore relationships between numerical variables.

5. **Visualization**  
   Created scatter plots with regression lines to visualize relationships, such as:
   - Tax 5% vs Gross income
   - Quantity vs Cost of Goods Sold (COGS)

---

## Technologies Used
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

---

## Getting Started

### Prerequisites
- Python 3.x installed
- Required libraries installed via:
  ```bash
  pip install pandas numpy matplotlib seaborn

  
