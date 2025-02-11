# Food-Hub


### Problem Statement

Due to Increasing of number of restaurants in NewYork day by day, Lots of students and busy professionals relay on those restaurants due to their hectic lifestyles, Online Food Delivery service is       great option for them.

FoodHub a food aggregator company offers access to multiple restaurants through a single smartphone app.

The app connects customers with restaurants, assigns delivery personnel to pickup confirmed orders, and facilitates delivery to customer using maps. Delivery is confirmed via the app, and customer can rate their experience. The aggregator earns revenue through a fixed margin on each order.

The company seeks to analyze its historical data to understand customer preferences, restaurant demand, and delivery dynamics. 
This analysis will help optimize operations, improve customer satisfaction, and enhance revenue streams.


### Data Dictionary

The Below is the data related to food order

* order_id : Unique ID of the order
* customer_id : ID of the customer who ordered the food
* restaurant_name : Name of the restaurant
* cuisine_type : Cuisine ordered by the customer
* cost_of_the_order : Cost of the order
* day_of_the_week : Indicates wheather the order is placed on a weekday or weekend.
* rating : Rating given by the customer out of 5
* food_preparation_time : Time (in minutes) taken by the restaurant to prepare the food.(diff between the restaurant's order confirmation and the delivery person's pick-up confirmation)
* delivery_time : Time taken by the delivery person to deliver the food package.(difference between the timestamps of the delivery person's pick-up confirmation and drop-off information)
