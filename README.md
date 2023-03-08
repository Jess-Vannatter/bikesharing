# bikesharing

## Overview of Analysis
- The goal of the bikesharing analysis was to put together several visualizations drawn from Data based on a successful bike sharing business in NYC and apply these visualizations in a way that would help sway investors in to backing the idea of starting a bike sharing business in Des Moines, Iowa. Of course, we could not draw from all bikesharing Data in NYC, so we chose one company, and drew from the data generated in August 2019. The month of August was chosen strategically, as it is a summer month, and it was assumed it would be a busier month with a higher rate of bike riders. Which would ultimately provide a larger data set to draw conclusions from.

- The analysis focused on certain aspects of the data set more than others. We really wanted to focus on who would be using our bike sharing service, when would they be using it, and how long would their trips be. Using the data set I believe we were able to address these questions with in depth visualizations that take in to consideration the type of user (customer/ subscriber ), the gender of our perceived user ( Male/ Femail/ Unknown ), the time frames with which each respected user type is likely to use our service, and the length of each type of users trip.

## Results


![Customer Types](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/Customer_types_viz.png)
- The Visualization above breaks down the type of customers that were using the bike sharing service in NYC during the month of August in 2019. It is broken down between just general customers using the service one ride at a time and customers that signed up for the subscription service and plan to use the bike sharing service more than once. Based on the visualization there are significantly more subscribed users than just general customers. Out of the 2,344,224 rides, 1,900,359 of them were carried out by subscribed users.

![Customers by Gender](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/Customers_By_Gender_Viz.png)
- Similar to the previous visualization, the one above breaks down the users by Gender. The figure shows that most of the users are male, with 1,530.272 of the overall users being make. There were 588,431 female riders as well with 225,521 user genders being unknown.

![August Peak Hours for Riders](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/August_Peak_Hours_viz.png)
- This graph clearly shows which hours throughout the day are busier than the others. .Here we see that there is a peak in the early morning around 7:00am and then again a couple of peaks in the afternoon from around 3:00pm to roughly 7:00pm. This could indicate that users are utilizing the bike sharing service for their work commutes. 

![Trips by Weekday per Hour](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/Trips_By_Weekday_Per_Hour_viz.png)
- Here we breakdown which hours on which days are busier than others. With the darker shades of orange representing the more active hours. You can see here that the 8:00am time frame along with 5:00pm and 6:00pm time frames are the most active (with the darkest shades). here we can assume in NYC that a lot of users are utilizing the bike sharing service for their work commutes. In addition, there is a pattern of darker shades that are consistent from 9:00am and 7:00pm on Saturdays and Sundays. This assumes that the users are riding for leisure on the weekends but for their work commutes during the week.

![Trips by Gender](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/Trips_by_Gender_viz.png)
- This Visualization breaks down the busier hours/ days even further by providing which genders are using the service and when. In correlation with the "Customers by Gender" visualization you can see much darker shades on the male section of the figure. Which tells us that makes are more than likely the ones using the service for their work commutes and on the weekends. But in general, the female figure follows the same pattern in that there are some using the service for their work commutes and for leisure on the weekends. Just not at the same rate.

![User Trips by Gender](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/User_trips_By_Gender_Viz.png)
- Building off of the same premises, we dig a little deeper to look in to which hours are busier on which days. But not only looking to which genders are using the service at what time on which day, but we break it down by user type as well. Again, you see the much darker shades of orange in the male column. But specifically, in the "Subscriber" row. Again, this correlates with the "Customer Types" figure referenced above that indicates that there are far more subscribers that use the service than just general, one-time user customers.

![Average Trip Duration by Age](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/Avg_trip_Duration_by_age_viz.png)
- I wanted to add this visualization because it tells us the age of our users. Which can help with promotions and who we want to possibly gear media campaigns towards. Even though the figure breaks down age and trip duration. You can clearly see a more consistent/ level line from users born in 1950 - 2000. The durations may not be extremely long, but we are getting no significant drops in usage. In the story we created, I made this chart filterable by gender as well which allows us to see which genders are using the service for longer trips.

![Checkout Times by Users](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/Checkout_Times_for%20Users_viz.png)
- Here we see a breakdown of the duration of trips. In most cases the trips do not last longer than 10 minutes and almost never lasting longer than an hour. So this indicates that a successful bikesharing service should be located in a close knit area. A lot of the residents in this area like to go out and see the neighborhood or work very close by. Which makes sense why NYC is a popular area for these services. A large Urban area is ideal, where more Rural locations may not work so well. 

![Checkout Times by Gender](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/Checkout_Times_by_gender_viz.png)
- Taking the previous visualization further we broke down the trip durations by gender. this aligns with the previous figures breaking down users by gender, as again Males are taking more trips and they are longer trips than Females. In fact it is significantly more. 

![Top Starting Locations](https://github.com/Jess-Vannatter/bikesharing/blob/main/images/Top_starting_Locations_viz.png)
- Lastly the map above shows which locations in NYC are utilized more. The larger/ darker spots on the map see a lot more foot traffic/ more riders utilize these are starting spots for their rides. I mainly utilized this figure to place in the story I created to show/ filter which genders, and user types are using these spots. There are a lot larger/ darker spots in the center of the city and on the western bank. Are these locations more touristy? Are these residential areas? By filtering by "User Type" we may be able to see which areas are used more by "Subscribers" or by "Customers". Subscribers would indicate that these are the people that live in the are, whereas customers might indicate tourists.

## Summary
- Please reference the Tableau story below. As it utilizes all of the figures/ visualizations above and interconnects them by allowing us to filter by not only "User Type'" but also by "Gender" to provide a better understanding of the analysis
  - [NYC Bikesharing Story](https://public.tableau.com/app/profile/jvannatter6/viz/Challenge_15_take_2/NYCBikesharingStory)


- In General, there are a couple of conclusions that can be drawn from the analysis presented above and correlate with the downtown/ urban area of Des Moines. Iowa being a valid location for a bike sharing service.
  - Males are far more likely to use the bikesharing service than Females. That could be for several reasons. I would link perceived safety as a possibly reason. As when riding a bike an individual is possibly more of an easier target for criminal acts such as robberies, attacks, etc. I would understand why women, especially in a more populated areas would feel safer driving there cars to work than riding bikes
  - Based on our data, Subscribers are far more likely to use the bikesharing service. Now this may be a direct result of the geographic location we chose. The general population in NYC does not own a car. They either work remote or work in the city, which makes sense for them to utilize a bike to get around. Becoming a subscriber to a bike sharing service like this could allow them to save money. This may not have the same effect in smaller or more rural areas.
 
 - Two additional visualizations that could be utilized to take the analysis further could possibly relate to breaking down the users by race and socio-economic status of the areas that are utilizing the service more.












