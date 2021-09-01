# Bikeshare dataset year 2019
## by Abdulrahman Osama


## Dataset

I have collected the data of bikeshare of all months year 2019 for two cities: San Francisco and Washington DC. I have read just the duration, start time, start and end station and the user type columns to decrease the size of the data. Each month was in a separate csv file so I appended them into one dataframe for each city and added a column with the city name then appended both dataframes into one dataframe. I also converted the start time column to datetime type and extracted from it three new columns: hour, day, and month.

I have uploaded the collected and tidy dataset with the whole project on my repository on github and can accessed with the following link
https://github.com/abdulrahmanosama/bikeshare

## Summary of Findings

The duration of trips is right skewed with overall average of 960 seconds.

Customers make longer trips than subscribers.

Trips over the weekends tend to be longer than the trips over the week days, while weekdays have more number of trips than weekends.

For the most common month of the year, in San Francisco March was the most common month for subscribers while surprisingly December was the most common month for customers. In Washington DC September was the most common month for subscribers while April was the most common month for customers.

For both subscribers and customers, week days have two peaks during the day one at 8:00 in the morning and the other at 17:00, where the weekends have their peak from noon to afternoon.

The distribution of the number of trips over the hours of the day and the day of the week for both cities was nearly the same.


## Key Insights for Presentation

    In the presentation, I start with the average and distribution of trips' duration then move how it differs for different types of users among cities and days of the week.

    Next I present the distribution of hour of the day among each day of the week and for different types of users then I move to the distribution of days of the week by each city and user type to focus on the idea how the users are using the bikeshare system in hteir daily life.
