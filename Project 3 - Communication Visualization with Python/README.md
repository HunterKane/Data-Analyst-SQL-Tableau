# Ford GoBike System Data Exploration 
## by Hunter Sparrow 


## Dataset

> The data consists of information regarding 183,000 rides made in a bike-sharing system covering the greater San Francisco Bay area. The data features include duration (secs) and others such as DateTime, customer type, gender, as well as some additional variables.

> The main issue is to remove unneeded columns and change datatype formats especially for columns that should be int are object. 

 Also missing data was removed for member_birth_year and member_gender. This had to be removed as the focus in on age and gender of riders.  


### Business background

Ford GoBike is expanding the area¡¯s existing bike-share program to 546 stations and 7,000 bikes ? serving San Francisco, San Jose and East Bay; riders can access GoBike through the FordPass.

Fastest-growing mode of transportation with usage surging 184 percent between 2006 and 2015, according to the San Francisco Municipal Transportation Agency.


### Questions to be analyzed 

- What time do people most use this service?
- What day of the week is most busy, least busy? (By user_type)
- What time of the day is the most demanding?
- Who uses this service the most? (subscribers / customers)
- Who uses this service the most by age and gender?
- How long to people normally use this bike?



## Summary of Findings

### Rent Hour Time:

- In the morning time 7-9am could be seen as the peak time for rentals. With 8pm having the highest start time.

- In the afternoon 4-6pm have a spike in start time with 5pm having the highest start time.

This could be due to working hours generally start and finish work from 8am-5pm / 9am-6pm working hours to and from work creating a higher demand for those times.

- Most trips taken are about 5-12 minutes

### Users:

- 71.2% are males and 22.3% are females. remaining is others/undefined

- 89% of users are subscribers with 71% of riders are male.

- Female Customers and subscriber user type spend more time riding

### Day:

- Thursday has the highest trips take by both customer and subscribers. However, Subscribers have over 30,000 trips but customers have less than 5,000 trips.

- Saturday and Sunday have the longest trip duration for both user types

### Trips by User:

Customers have longer duration of trips on Saturday and Sunday
This could be a reason that tourist use the service when traveling to that area having longer trip durations exploring a new area. Whereas subscribers might use it for work reasons getting to and from work with much shorter trip durations. Also there about 90% subscribers meaning the average appears lower compared to customers.

### User Age:

- Age 25-35, has the highest age range. Whereas, ages 45-65 being on the lower end of the age distribution.

- The Mean user age is 34 years old.


## Key Insights for Presentation

In this presentation I focused on the who(demographics of age, gender) the peak hours of users and the difference between user type rental for days of the week.

The who:

A histogram was used to show the distribution of riders by age. Age 25-35, has the highest count. Whereas, ages 45-65 being on the lower end of the age distribution.

A pie chart was used to show the ratio of genders. 71.2% are makes and 22.3% are females. Other 6.5% percent was not defined or other. 


Peak Hours:

a countplot was used to show the rental_start times people use the service. - In the morning time 7-9am could be seen as the peak time for rentals. With 8pm having the highest start time. In the afternoon 4-6pm have a spike in start time with 5pm having the highest start time. Thursday has the busiest rental day for Subscribers. 


User type:

A line plot was used to show the average duration customers versus subscribers used the bike service. Customers use the bike serive more than cusotmers especially on Saturdays and Sundays. 

