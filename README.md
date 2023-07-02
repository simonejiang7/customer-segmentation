# Customer Segmenation Exercise

### Task 1

1. Describe the datasets and the eventual anomalies you find.
2. What are the most popular items in the store catalog? Can you provide a list of the top 10 items ordered by customers?
3. What is the overall revenue generated by the orders in the dataset? How does the revenue vary by time period ?
4. Which general patterns do you find in the purchasing behavior of the customers?
5. Split customers into different groups based on their purchasing behavior.
    * Justify your choice for your adopted method(s) and model(s).
    * Describe the defined customer groups. What are the features which are driving the differentiation amongst the different groups?
    * Give suggestions on how the business should treat these clusters differently.
    * Which clusters seem to have the highest ROI ? 
6. At this point in your analysis, you are the dataset expert. Implement in your notebook any further ideas (initiatives, further analyses) you might have in mind which can be helpful for the business.
**We strongly encourage you to develop your ideas/analyses in your notebook.**

**Note**: You will need to make assumptions for completing this task. Also, keep in mind that there is no ‘right’ or ‘wrong’.

### Task 2

**Note**: Explain and justify your thinking process. Be creative but also realistic.

You are the lead eCommerce Data Scientist in a well-known car company, and this task requires you to come up with ideas for the following digitalization problem:

The website is currently used to showcase all your vehicle models available for sales. Your users can access a page with all models, and can also configure their dream car.
However the user experience is mostly static, and as a data scientist your role is to come up with new ideas to personalize and enhance the user experience on the website. 

**Leading points**:

* What data products do you have in mind to solve that problem?
* What kind of data do you need?
* What are the limits/shortcomings of your ideas?

## Metadata
Files and names should be self explanatory.

events.csv

Contains user behavior data events. For example click which are associated with features (timestamp, platform ..).

```
event_id, event_time, user_id, event_name, platform, parameter_name, parameter_value 
b9de71c5c3cc4cd7a97e50b832106e5a, 2017-06-26 11:23:29, 178481, view_item, android, item_id, 3526 
...
```

items.csv

Contains items information like name, price or category.

```
adjective, category, created_at, id, modifier, name, price
fuzzy, contraption, 2014-01-15 21:36:09, 2512, carrying_case, fuzzy contraption carrying_case, 150.0
... 
```
orders.csv

Contains information for each order. For exemple, paid_at represents when the order has been fully payed.

```
invoice_id, line_item_id, user_id, item_id, item_name, item_category, price, created_at, paid_at
192320.0, 83118, 178481, 3526, digital apparatus, apparatus, 330.0, 2017-06-28 21:14:25, 2017-06-27 21:19:39
...
```

users.csv

Contains user information with features like email_address, last_name, first_name.
```
created_at, deleted_at, email_address, first_name, id, last_name, merged_at, parent_user_id  
2014-12-20 07-07-45, None, ArataHopper@gmail.com, Arata, 51590, Hopper, None, None 
...
```
**Have fun!**
