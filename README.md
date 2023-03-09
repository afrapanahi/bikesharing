# Bike sharing
## Overview of Project 
In this project, we are looking at the bike sharing and bike usage. We will break it down to users, days of the week and gender.
To do this, we first convert the tripduration to date and time using pandas (see image below)
![fig1](/img/pic1.png?raw=true "Tripduration in pandas")

Then using Tableau, we analyze the data.
## Results
In our analysis, we are investigating the following questions:
-	1. What are the user types? 
As depicted  in the following, from total of 2,344,224 users, 443865 are subscribers (image below) 
![fig2](/img/pic2.png?raw=true "usage")

-	2. What are the most popular locations for bike usage?
As depicted below (see image) Majority of trips start in the south of city.
![fig3](/img/pic3.png?raw=true "locations")


-	3. What are the most common trip durations? (see image below)
Figure 1: Maximum of ~147,000 bikes were checked out for 6 min trip duration 2. Figure 2: For male maximum of ~108,000 bikes were checked out for ~5 min while for women maximum of ~34,000 bikes were checked out for 7 min. For costumers with unknown gender this value 6,000 for 6 to 25 min.
![fig4](/img/pic4.png?raw=true "duration")

-	4. What is the bike usage in each day of the week? (see image below)
The majority of trips are done on Thursdays from 5-7 PM. Most of the trips are done in the evenings. Thursday 7:00 am has the most number of trips in the mornings as well.
![fig5](/img/pic5.png?raw=true "weekday")

-	5. What is the bike usage in each day of the week for different genders? (see image below)
The following graph depicts number of trips based on gender. Both Male and female users are showing the same trend with make users significantly larger number of bike trips. Similar to the last graph, for both male and female users, maximum trips are done on Thursdays from 5-7 PM. Most of the trips are done in the evenings. Thursday 7:00 am has the most number of trips in the mornings as well.
![fig6](/img/pic6.png?raw=true "weekday gender")

-	6. What is the bike usage broken by hour?  (see image below)
In this graph, trips are broken down by days, gender and subscribers vs customers. It is interesting to see that majority of trips are done by male subscribers on Thursdays following closely by Wednesday. While the same trend is observed in female subscribers, the number of trips are smaller.
![fig7](/img/pic7.png?raw=true "weekday gender hour")


[Link to dashboard]( https://public.tableau.com/app/profile/afra6425/viz/NYC2_16782566120850/NYCbikes?publish=yes)

## Summary

We observed that there are specific locations in the city where bike trips tend to be popular. The data also suggests that Thursdays’ morning and afternoon has the highest bike users among male and female subscribers.

Additional analysis: 1. Why Thursdays are common among the users? A closer look at the data i.e. different locations at different hours of Thursday may help with understanding with the trend.
2. We observed that several locations are more popular for bike sharing. Additional analysis such as breaking the locations down by gender may help us understand if these spots are common among all users.

