# Link to the Jupyter Notebook

https://github.com/msach05/module5berk

# What is this project about?
The goal of this project is to use data analysis techniques about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

# Where is the data from
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’.  There are five different types of coupons -- less expensive restaurants (under \$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\$20 - $50).

# What did I do?
This notebook focuses on analyzing customer behavior to predict whether they will accept a coupon based on a dataset of user attributes and situational factors. It begins with an introduction to the context and deliverables, aiming to differentiate between customers who accept or reject coupons. The data includes attributes such as gender, age, and situational characteristics. I use Python libraries like Pandas, Matplotlib for data manipulation and visualization. The notebook guides through exploratory data analysis steps, starting with reading a CSV file, visualizing distributions, and identifying patterns in the data.
# Conclusion

Customers who are most likely to accept coupons are young (under 31), single individuals without children, traveling to non-urgent destinations with friends, during sunny weather and higher temperatures (above 70°F). They tend to prefer coupons for carryout, takeaway, or affordable restaurants (under 20 dollar) and are more responsive to coupons with a 1-day expiration. Acceptance rates are also higher during meal-related times such as 10 AM, 2 PM, and 6 PM. Income levels show higher acceptance among those earning less than $62,499 or over $100,000, while gender and bar visits do not significantly impact acceptance.