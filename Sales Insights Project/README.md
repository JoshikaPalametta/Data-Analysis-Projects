# Sales Insights Project

## Project Overview

The **Sales Insights Project** is a data analysis project aimed at providing actionable insights from a retail dataset. Using Python and popular data analysis libraries, this project explores sales trends, top-performing products, categories, regions, and customers to support data-driven business decisions.
---

## Dataset

The dataset used in this project is a **retail sales dataset** containing 9,800 records with the following key columns:

* `Order ID` – Unique identifier for each order
* `Order Date` – Date when the order was placed
* `Ship Date` – Date when the order was shipped
* `Customer Name` – Name of the customer
* `Region` – Region where the order was delivered
* `Category` & `Sub-Category` – Product classification
* `Product Name` – Name of the product sold
* `Sales` – Revenue from each order
* `Profit` – Profit from each order (if available)

> **Note:** The dataset can be downloaded from [Kaggle Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).

---

## Project Features

* **Data Cleaning:** Handles missing values and ensures proper data types for analysis.
* **Feature Engineering:** Calculates profit margin and extracts month from order date.
* **Sales Analysis:**

  * Total Sales, Total Profit, and Average Profit Margin
  * Top 10 products by sales
  * Sales distribution by category
  * Monthly sales trends
  * Sales by region
  * Top 10 customers by sales
* **Data Visualization:** Interactive plots using Matplotlib and Seaborn to present insights clearly.
* **Insights:** Actionable recommendations for marketing, inventory, and customer targeting.

---

## Technologies Used

* **Python 3.x**
* **Pandas** – Data manipulation and analysis
* **Matplotlib** & **Seaborn** – Data visualization
* **Google Colab** – Cloud-based notebook environment for execution

---

## How to Run

1. Clone the repository to your local machine or open it in **Google Colab**.
2. Upload the `train.csv.zip` dataset when prompted.
3. Run all code cells to perform data cleaning, analysis, and visualization.
4. Explore the insights and visualizations generated in the notebook.

---

## Insights

* Focus on **top-selling products and categories** for inventory and marketing decisions.
* Monitor **monthly sales trends** to identify peak seasons.
* Target **high-sales regions** and **top customers** for loyalty and retention programs.

---

## Project Scope

This project can be extended to:

* Analyze **customer segmentation** for targeted marketing.
* Predict **future sales** using machine learning models.
* Scale to **Big Data** using Dask or PySpark for larger datasets.



