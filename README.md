FoodHub Data Analysis

Overview

This project analyzes historical food order data from FoodHub, a food aggregator platform. The goal is to understand customer preferences, restaurant demand, and delivery dynamics to optimize operations and improve customer satisfaction.

Problem Statement

With the increasing number of restaurants in New York, many students and professionals rely on food delivery services. FoodHub provides a platform that connects customers with restaurants, facilitates order processing, assigns delivery personnel, and collects customer ratings. The company aims to analyze its historical data to enhance revenue and optimize operations.

Dataset

The dataset contains details about food orders, including:

order_id: Unique ID of the order.

customer_id: ID of the customer who placed the order.

restaurant_name: Name of the restaurant.

cuisine_type: Type of cuisine ordered.

cost_of_the_order: Cost of the order.

day_of_the_week: Indicates whether the order was placed on a weekday or weekend.

rating: Customer rating of the order (out of 5).

food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food.

delivery_time: Time (in minutes) taken by the delivery person to deliver the food.

Tools & Libraries Used

Python

Pandas (for data manipulation)

Seaborn and Matplotlib (for data visualization)

Installation & Usage

Clone the repository:

git clone https://github.com/yourusername/FoodHub-Data-Analysis.git
cd FoodHub-Data-Analysis

Install dependencies:

pip install pandas seaborn matplotlib

Run the Jupyter Notebook:

jupyter notebook FoodHub_Project.ipynb

Analysis & Insights

The notebook performs:

Data loading and preprocessing

Exploratory Data Analysis (EDA)

Visualization of key trends (restaurant demand, ratings, delivery times)

Insights for optimizing delivery operations and customer experience

Results

Some key findings include:

The impact of cuisine type on order volume.

Trends in delivery times and food preparation times.

Customer rating patterns.

Future Improvements

Implement predictive analytics for delivery time estimation.

Optimize restaurant and delivery assignments.

Enhance customer experience through personalized recommendations.

Author

[Your Name]

License

This project is licensed under the MIT License.
