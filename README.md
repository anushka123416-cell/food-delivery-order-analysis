# food-delivery-order-analysis
A beginner-friendly data analysis project built in *Google Colab* using *Python, **Pandas, and **NumPy* to explore food delivery order data, order categories, interactive restaurant/item searches, and order discounts.

## Dataset Overview
- *File:* order_history_kaggle_data.csv (Kaggle food delivery order history dataset)
- *Size:* 21,321 rows and 29 columns
- *Key Columns:* Restaurant name, Order Status, Items in order, Bill subtotal, Total, Rating, KPT duration (minutes), Rider wait time (minutes), and discount columns (Restaurant discount (Promo), Restaurant discount (Flat offs, Freebies & others), Gold discount).

## Tools & Libraries Used
- *Python*
- *Pandas* (CSV loading, column cleaning, filtering, and value counts)
- *NumPyA*- (mean, median, std, max, sum, and conditional categorization via np.where)
- *Google Colab*

## Key Features Implemented
1. *Dataset Loading & Inspection:* Loads the CSV, cleans column names, checks dataset shape and missing values, and displays user-selected top orders.
2. *Numerical Summary:* Computes Mean, Median, and Standard Deviation for numeric columns using NumPy.
3. *Order Categorization:* Classifies orders into Small (<200), Medium (200-500), and Large (>500) based on Bill subtotal using np.where.
4. *Interactive Search:* Allows filtering orders dynamically by *Restaurant name* and *Food item*.
5. *Discount Analysis:* Calculates average discount per order, maximum discount given, and total discount across all orders.

## How to Run
1. Open food_analysis_project.ipynb in *Google Colab* or on your local system.
2. Ensure order_history_kaggle_data.csv is available in your working/Colab environment.
3. Run the cells sequentially and enter inputs when prompted.
  
