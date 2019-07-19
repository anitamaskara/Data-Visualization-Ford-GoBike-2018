# Ford-GoBike-2018---Data-Visualization

### Introduction
Bay Wheels offers all residents of the Bay Area an affordable, accessible and fun new transportation option. Bikes available 24/7/365 in San Francisco, Oakland, Berkeley, Emeryville and San Jose. One-time \\$5 Annual Membership (\\$5/month in second year). Membership includes first 60 minutes of each trip.Rides longer than 60 minutes will result in additional fees of $3 for each additional 15 minutes or potential account suspension.

The data is available at <a href="https://s3.amazonaws.com/baywheels-data/index.html"> https://s3.amazonaws.com/baywheels-data/index.html</a>

The dataset includes data for the year 2018. It has $1863721 $ rows and $16$ columns

### The data
Each trip is anonymized and includes:

Trip Duration (seconds)<br>
Start Time and Date<br>
End Time and Date<br>
Start Station ID<br>
Start Station Name<br>
Start Station Latitude<br>
Start Station Longitude<br>
End Station ID<br>
End Station Name<br>
End Station Latitude<br>
End Station Longitude<br>
Bike ID<br>
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)<br>
Member Year of Birth<br>
Member Gender
Bike share for all

'Bike share for all' is a program which is offered by Ford goBike to sponsor low income people who meet certain criteria. Bike Share for All is available to Bay Area residents ages 18 and older who qualify for Calfresh, SFMTA (Low Income) Lifeline Passes or PG&E CARE utility discount. 

### Summary of findings
The exploration was carried out keeping marketing and sales in mind about the target customer on the basis of age, gender and type of user

I found that 
- majority of the riders fall in the age group of 20 to 40 years old. The lower age group and the higher age groups have relatively fewer bike rentals.
- the trip duration is around 10 minutes indicating that majority of the riders tend to rent a bike for short trips.
- A large majority of the bike rentals are from subscribers who use the bikes to fulfill their conveyance needs.Subscribers accounted for 88.6$\%$ of total number of bike rides in 2018 while customers accounted for the remaining 11.4$\%$
- A large majority of the bike riders are male. 
- People prefer to ride more during summer and fall season when the weather is also conducive. Pollen allergies during spring season is quite common in these areas and that might be one reason for low number of bike rides during spring. Winters are also not preferred because of the cold and windy weather conditions.
- The number of bike rides increase steadily for all the age groups till May. Between May and October, the highest growth happens for age group of 20-30 and 30-40. The remaining three groups have marginal increase between May and October. After October, the growth for all age groups tapers off. The weather plays a key role in this pattern. During the spring months and summer months, the number of rides increase. With the onset of autumn season, the number of rides start to decline gradually.
- The average distance (in miles) is very similar for both the user types, but the average trip duration for customers (26 minutes) is more than two times the average trip duration for subscribers (11 minutes). The average trip duration traveled by customers is more than double that of subscribers irrespective of weekday or weekend.

## Key Insights

> Majority of the trips are undertaken by riders fall in the age group of 20 to 40 years old. The lower age group and the higher age groups have relatively fewer bike rentals.

> 3 out of 4 riders are male. Although the trip duration is longer for trips undertaken by female riders

> The trip duration is around 10 minutes indicating that majority of the riders tend to rent a bike for short trips.

> People prefer to ride more during summer and fall season when the weather is also conducive. Pollen allergies during spring season is quite common in these areas and that might be one reason for low number of bike rides during spring. Winters are also not preferred because of the cold and windy weather conditions.

> Subscribers ride more during the hours of 7:00 am to 9:00 am and 16:00 pm - 19:00 pm on weekdays. Customers ride more during the hours of 16:00 pm and 19:00 pm. This coincides with the peak hours for traveling to and from office. The usage pattern is distinctly different between the two user types on weekends. Customers ride more during the hours of 10:00 am to 17:00 pm on weekends.

