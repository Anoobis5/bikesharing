# bikesharing
![depositphotos_377303356-stock-illustration-bike-sharing-business-minimal-infographic](https://user-images.githubusercontent.com/84881187/132614993-97d52638-be50-4915-bc15-4f2c48e1c385.jpg)


## Project Overview

Based on our August 2019 ridesharing data, the CitiBike program in New York City is doing very well. This success indicates that there is potential to expand bike sharing programs to other metropolitan cities, such as Des Moines, Iowa. 

For our proposal, we used Pandas to change the "tripduration" column from our '201908-citibike-tripdata' file from an integer into a 'datetime' datatype. We then used the converted datatype to create a set of visualizations that will allow the reader to see:

  * See the length of time that bikes are checked out for all riders and genders.
  * See the number of bike trips for all riders and genders for each hour of each day of the week.
  * See the number of bike trips for each type of user and gender for each day of the week.

We then added these visualizations to the two visualizations we made prior to transforming our datatype data. Please [click here to view the completed Dashboard](https://public.tableau.com/shared/3235TF8T7?:display_count=n&:origin=viz_share_link) to view the complete story proposal.

## Results

Looking at the over 2 million users of the Citibike program, about 65.28% of the users are men, and 81.07% of the users are subscribers to the program as opposed to casual customers. 

![Rider Topography](https://user-images.githubusercontent.com/84881187/132776138-9bf5297b-d3ac-4dc4-9f3a-77f690eb30e6.PNG)



According to the [US Census Bureau](https://www.census.gov/quickfacts/fact/table/newyorkcitynewyork,desmoinescityiowa/PST045219) the gender ratios in NYC are similar to those in Des Moines Iowa. In July of 2019, Des Moines was comprised of roughly 50.7% female, where NYC was 52.3% female. This could indicate that there could be similar trends based on gender demographics alone. In New York City, the highest density of Top Starting and Top Ending locations for Citibike trips occur most frequently in mid-town Manhattan, where there are many offices and businesses with commuter employees. The highest density trip areas also correlate to popular tourist locations; as well as popular hotel locations. 

![Location Density](https://user-images.githubusercontent.com/84881187/132614892-7ddec200-ce2b-4178-a132-aa8b09f66bb0.PNG)


When we look at the length of time for each bike rental, along with the number of rentals, we see that the majority of rentals are less than 30 minutes. This lets us know that it would be beneficial for the bikesharing service to cover the release demands of the potential users. Looking at the gender graph, the trend correlates to the amount of users, as there tend to be more male users. Male users also take slightly longer trips. 


![Checkout Times](https://user-images.githubusercontent.com/84881187/132615718-fb5e2bd5-0d85-44a7-ae23-7c7d58a3b991.PNG)

Looking at the Checkout Times by Gender, we see a similar trend to to the user population. Males make us a majority of users and tend to take slightly longer trips, but overall rental times appear to be fairly equal across all genders. 


Looking at our Trips by Dat of the Week graph, we see that Thursday has significantly more users than any other day of the week. 

![Trips by Day](https://user-images.githubusercontent.com/84881187/132772132-e0a91e71-7abc-4203-ab80-2b873283be0f.PNG)

When we examine our Peak Hours for the month of August, 2019, we can observe that the highest number of users is during 5pm - 7pm


When we join this data, our Trips By Hour chart shows that Thursdays at 5pm - 6pm definitely have the highest density of users on the road.

![Trip By Hour](https://user-images.githubusercontent.com/84881187/132772522-14587e36-43e2-46d2-99d0-0f41d33bd86a.PNG)

When we take a closer look at the data in our Trip By Day per Hour chart, we can see that Male users do indeed make up a significant portion of the traffic on Thursday afternoons, as well as Monday, Tuesday, and to an extent Friday during the peak 5pm - 7pm time slots.

![Trip By Hour by Gender](https://user-images.githubusercontent.com/84881187/132772825-6a9f59e2-33c2-4d3c-b8b1-c40f32560a4c.PNG)


Looking at our Trips by Weekday Topography chart, we can see that the majority of users during those Thursday rush-hours are primarily Male Users that are subscribers to the service. This could indicate that a significant number of the users are not only tourists, but business men, local to the area, using the service on a regular basis to commute to and from work. Non-subscribers tend to use the service more during the weekend days. 

![Trip by Weekday topography](https://user-images.githubusercontent.com/84881187/132772626-307580e6-55b2-47ab-9c5a-93bca8fc1098.PNG)


## Proposal Summary

Looking a the data visualized in our proposal, we see that the vast majority of our bikesharing service's users will potentially from from Male Subscribers that will be using the bikesharing service to commute to and from work during the morning and evening. This gives our marketing team a good target group to focus on for attracting initial subscribers. The next most popular times are weekends. Looking at our NYC Citibike data, we can also target tourists and anyone going out to recreational areas of interest in our marketing strategies.

Before starting up our service, we need to make sure that the company invests in acquiring a large quanity of bike to meet the potential demand upon release. Bike trips tend to last on average less than 30 mins. This means there will be quite a bit of availability circulation at different bike stations. Our Top Starting and Top Ending Chart gives a good idea of this kind of trend.

Our bike sharing service could target the metropolitan area to get similar trends to NYC's successful Citibike program; but there are many other untapped variables we could advertise to. While in NYC, we dont have as much CitiBike usage data in other boroughs outside of Manhattan, we could target biking trails and rural areas outside of the Des Moines metropolitan area as potential zones to set up Bike Rental Stations. Overall, our data shows that opening a bike sharing service in Des Moines will be beneficial to the community and the environment. 

