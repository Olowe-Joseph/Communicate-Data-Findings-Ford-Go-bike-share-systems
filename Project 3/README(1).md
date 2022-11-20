# (communicate findings: Ford go-bike project)
## by (Olowe joseph)


## Dataset

 This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset consists of information regarding 183,412 rides made in a bike-sharing system covering the greater San Francisco Bay area. The data features include duration (secs) and others such as DateTime, customer type, gender, and some additional variables.


## Summary of Findings
 
 The duration_min data did not show a proper distribution while plotting them on the linear scale so i plot them on the logarithmic scale to have the proper distribution, I calculated the age of the users using the member_birth_year, i assumed the name of the csv file which is '201902' to be 2019 february as 02 means the second month of the year so i used 2019 in calculating the members age, the tripping duration was initially at seconds but I converted them to minutes for easier analysis, also the duration_min distribution had outliers so I removed them and finally, I extracted the hour of the day and the day of the week from the timestamp.


## Key Insights for Presentation

  I found that the users used the bike for a wider range of trip duration, also, after cleaning the trip duration data and removing the outliers, I found that the major trips had a trip duration on average of 7-12 mins. We can also see that the work days were the most days that the users use the bike share system the most, especially on Thursdays. We can see that the time most users ride the bike were around 8 A.M and 5 P.M and this looks more like the starting and closing time for companies. As for the users, we can see that the male users are almost 3 times the female users, the most age range is 25-35 and the subscriber users are almost 9-10 times the customer users.