#  Sales Data Analysis using Python

## Project Overview

This project analyzes a year's worth of electronics sales data to uncover business insights using Python. The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), and visualization to answer important business questions related to sales performance, customer purchasing behavior, and product demand.

The project demonstrates practical use of Python for data analysis using Pandas and Matplotlib.

---

## Objectives

- Clean and prepare raw sales data
- Merge monthly sales datasets into a single dataset
- Perform feature engineering
- Analyze sales trends
- Identify best-performing cities and months
- Discover customer buying patterns
- Find products frequently purchased together
- Visualize insights using charts

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Dataset

The dataset contains electronic product sales information including:

- Order ID
- Product Name
- Quantity Ordered
- Price Each
- Order Date
- Purchase Address

---

## Data Preprocessing

The following preprocessing steps were performed:

- Merged monthly sales files into one dataset
- Removed missing values
- Removed duplicate header rows
- Converted columns into appropriate data types
- Created new features:
  - Month
  - Sales
  - City
  - Hour
  - Minute

---

## Business Questions Answered

### 1. Which month generated the highest sales?

Analyzed monthly sales revenue to identify the best-performing month.

---

### 2. Which city had the highest sales?

Compared total sales across cities to determine the highest revenue-generating location.

---

### 3. What is the best time to display advertisements?

Analyzed order frequency by hour to identify peak customer purchasing times.

---

### 4. Which products are frequently bought together?

Used transaction analysis with combinations and collections. Counter to identify common product pairs.

---

### 5. Which products sold the most?

Compared product quantities sold and explored the relationship between product price and sales volume.

---

## Visualizations

The project includes several visualizations:

- Monthly Sales Bar Chart
- Sales by City
- Orders by Hour
- Most Sold Products
- Product Quantity vs Price Comparison

---

## Project Structure

```
Sales-Data-Analysis/
│
├── Sales_Project.ipynb
├── Sales_April_2019.csv
├── README.md
├── requirements.txt
└── images/
    ├── monthly_sales.png
    ├── city_sales.png
    ├── orders_by_hour.png
    ├── products_together.png
    └── product_sales.png
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Sales-Data-Analysis.git
```

2. Install required libraries

```bash
pip install pandas matplotlib numpy
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run the notebook cells.

---

## Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Business Analytics
- Data Visualization
- Python Programming
- Pandas
- Matplotlib

---

## Future Improvements

- Interactive dashboard using Power BI or Tableau
- Sales forecasting using Machine Learning
- Customer segmentation
- Product recommendation system
- Interactive visualizations using Plotly

---

## Author

**Mohd Arhab Ahmad**

- MSc Statistics
- Python | SQL | Power BI | Data Analytics


