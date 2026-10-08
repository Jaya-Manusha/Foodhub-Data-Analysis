# 🍔 FoodHub Data Analysis

## 📌 Project Overview

This project focuses on analyzing **FoodHub food order data** to understand customer behavior, restaurant performance, order trends, and factors influencing customer ratings.

The analysis uses Python and data visualization techniques to extract meaningful business insights that can help FoodHub improve its operations and customer experience.

## 🎯 Objectives

- Analyze overall food ordering patterns.
- Identify the most popular restaurants.
- Analyze customer ordering behavior.
- Understand the distribution of food preparation and delivery times.
- Identify the most popular cuisines.
- Analyze customer ratings.
- Understand the relationship between order characteristics and customer satisfaction.
- Provide actionable business recommendations.

## 🗂️ Dataset

The dataset contains information about food orders placed through FoodHub.

Key columns include:

- `order_id` – Unique order identifier
- `customer_id` – Unique customer identifier
- `restaurant_name` – Name of the restaurant
- `cuisine_type` – Type of cuisine ordered
- `cost_of_the_order` – Cost of the order
- `day_of_the_week` – Day on which the order was placed
- `rating` – Customer rating
- `food_preparation_time` – Time required to prepare the food
- `delivery_time` – Time required to deliver the order

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Analysis environment

## 🔍 Analysis Performed

### 1. Data Understanding

- Loaded the FoodHub dataset.
- Examined the dataset structure.
- Identified numerical and categorical variables.
- Checked dataset dimensions and data types.

### 2. Data Cleaning

- Checked for missing values.
- Identified duplicate records.
- Converted columns to appropriate data types.
- Handled missing or inconsistent values where required.

### 3. Exploratory Data Analysis

The analysis covers:

- Number of orders
- Unique customers
- Restaurant performance
- Cuisine popularity
- Order cost distribution
- Customer ratings
- Food preparation time
- Delivery time
- Weekday vs. weekend ordering patterns

### 4. Data Visualization

Visualizations were created to understand:

- Most popular restaurants
- Most popular cuisines
- Distribution of order costs
- Distribution of customer ratings
- Food preparation time
- Delivery time
- Orders by day of the week
- Relationship between delivery time and customer ratings

## 💡 Key Insights

The analysis helps identify:

- Restaurants receiving the highest number of orders.
- Cuisines that are most popular among customers.
- Typical customer spending patterns.
- Restaurants with strong customer satisfaction.
- Average food preparation and delivery times.
- Differences in ordering behavior between weekdays and weekends.
- Factors that may influence customer ratings.

## 📈 Business Recommendations

Based on the analysis, FoodHub can:

- Focus on partnerships with high-performing restaurants.
- Promote popular cuisines through targeted offers.
- Improve delivery efficiency to enhance customer satisfaction.
- Identify restaurants with consistently low ratings and work with them to improve service.
- Use customer ordering patterns to optimize promotional campaigns.
- Introduce personalized recommendations based on customer preferences.
- Monitor food preparation and delivery times to improve the overall customer experience.

## 📁 Project Structure
```

FoodHub-Data-Analysis/ │ ├── FoodHub_Data_Analysis.ipynb ├── foodhub\_order.csv ├── README.md └── images/ └── visualizations/

```

## 🚀 How to Run the Project

### Step 1: Clone or Download the Repository

Download the project files to your local machine.

### Step 2: Install Required Libraries
```

pip install pandas numpy matplotlib seaborn jupyter

```

### Step 3: Launch Jupyter Notebook
```

jupyter notebook

```

### Step 4: Open the Notebook

Open:
```

FoodHub_Data_Analysis.ipynb

```

Run the notebook cells sequentially to reproduce the analysis.

## 📌 Conclusion

The **FoodHub Data Analysis** project demonstrates how exploratory data analysis and visualization can be used to understand food ordering behavior and customer satisfaction.

The insights generated from this analysis can help FoodHub make data-driven decisions related to **restaurant partnerships, customer engagement, delivery efficiency, promotions, and overall service quality**.

## 👤 Author

**Jaya Manusha**
