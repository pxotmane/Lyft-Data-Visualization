# Lyft-Data-Visualization
### Introduction

This project is about Bay Wheels (called also Ford GoBike after a partnership with Ford Motor Company) routes for public use data set. Bay Wheels is a regional public bicycle sharing system in the San Francisco Bay Area, California. It's owned by Lyft, the system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.

### Technologies Used
- Python, Numpy, Pandas, Matplotlib, Seaborn
- LaTex
- Jupyter Notebook  
 
### The structure of dataset

This dataset contain 519700 observations and 13 features.

- Four columns are integer(duration_sec, start_station_id, end_station_id, bike_id). 

- Five columns are object where start_time and end_time are timestamp, while that start_station_name, end_station_name, user_type are string. 

- Four columns are float (start_station_latitude, start_station_longitude, end_station_latitude, end_station_longitude). 

I convert duration_sec to time readable format and I calculate the distance tracks from latitude and londitude columns. Also I extract the year, month and day from start_time column. Which mean I added 5 other columns to my dataset. 

Also I've eliminated outlier values from all data frame columns. This reduces the number of observations to 357900 instead of 519700.
 
### The main feature of interest in dataset

I am interested in this new concept of renting bikes, I want analysis the time and distance traveled by each consumer and know which type of consumers is more  useable of Lyft services.

### The features in the dataset help support my investigation into my feature(s) of interest

 There are two types of bike users (Customer, Subscriber) I want to know which one uses the bikes more and for how long, thus the top 10 most popular start and finish stations in the city.

Exploratory data visualization consists of 3 steps:

- **Univariate Exploration :** to get an idea about the distribution of one variable;

- **Bivariate Exploration :** to get and idea about the relationship of two variables;

- **Multivariate Exploration :** to get and idea about the relationship of three variables

> More details in the project notebook below

### Key findings

It is normal that a duration of use of Lyft bicycles services must be higher among Subscribers than Customers. But in our studies we find that the duration average for Customer users is more than Subscribers users.

 This generates results that pushes the company to review its marketing policy, maybe can encourage Customers users with new offers for traveling long distances and more time.
