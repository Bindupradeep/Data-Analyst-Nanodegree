# Bay Wheels System Dataset
## by Bindushree

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Their eye-catching bikes are durable, easy to use, and built to fit everyone.The Classic bicycles were designed for easy riding in an urban environment. They were built to be comfortable for any type of rider, regardless of height, or riding ability. This first-of-its-kind hybrid ebike allows you to dock at any Bay Wheels stations or use the cable to lock to any bike rack within the service area. With miles of service area and nearly 400 stations, Bay Wheels gets you where you’re going. 
You can find the dataset here: https://www.lyft.com/bikes/bay-wheels/system-data

### Data Wrangling Process
1. The datatypes of the columnsstart_time, end_time and user_type columns are incorrect. Change the datatypes to datetime and category respectively.
2. Create new columns for day, month and week by splitting the start_time and end_time for analysis. 
3. Create a new column hour by splitting the start_time column for analysis.
4. Change the datatype of the month and week column to category.

## Summary of Findings

1. When performing the wrangling and visualization process, I was focusing mainly on the trips performed on a weekly/monthly/hourly basis on the two types of users and their behaviour in the Bay Wheels. The proportion of subscribers were more than a quarter as compared ot the customer users. 
2. The number of trips were the most on the weekdays for subscribers and on weekends for the customers. Most number of trips from subscribers were mostly between 8hr and 9hr and betweeen 17hr and 18hr. Where as from customers most number of trips was in the afternoon and early evenings (between 12hr and 17hr). 
3. The trip duration for subscribers is less compared to the customers(between 10 minutes to 15 minutes).


## Key Insights for Presentation

1. Overall, we can say that there are different behavioural features between subscribers and customers. Subscribers use the bikes frequently during the weekdays may be for work purpose that is easy and affordable for mobility. Most of the trips are mostly during the mornings and evenings which implies that subscribers use the bikes to go to the work place in the morning and get back home by evenings. The trip duration is less compared to the customers because they might use the bike for work commute only. Being a subscriber user is more advantageous for office goers or students on a daily basis because of the flexibility, discounts and also for frequent travel on a day to day basis, etc.
2. On the other hand, customers use bikes frequently on the weekends for their leisure time may be go for cycling, etc. Their trips are usually during the afternoon and early evenings which implies that they use bikes for a different purpose. The duration of the trip by customers is for a longer time which implies they are more relaxed and more flexible with respect to the time duration.