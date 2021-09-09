# bikesharing
![depositphotos_377303356-stock-illustration-bike-sharing-business-minimal-infographic](https://user-images.githubusercontent.com/84881187/132614993-97d52638-be50-4915-bc15-4f2c48e1c385.jpg)


## Project Overview

Based on our August 2019 ridesharing data, the CitiBike program in New York City is doing very well. This success indicates that there is potential to expand bike sharing programs to other metropolitan cities, such as Des Moines, Iowa. 

For our proposal, we used Pandas to change the "tripduration" column from our '201908-citibike-tripdata' file from an integer into a 'datetime' datatype. We then used the converted datatype to create a set of visualizations that will allow the reader to see:

  * See the length of time that bikes are checked out for all riders and genders.
  * See the number of bike trips for all riders and genders for each hour of each day of the week.
  * See the number of bike trips for each type of user and gender for each day of the week.

We then added these visualizations to the two visualizations we made prior to transforming our datatype data. Please [click here to view the completed Dashboard](https://public.tableau.com/views/NYC_CitiBike_bikesharing_Challenge/NYC_Bikesharing_Challenge?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) to view the complete story proposal.

## Results

Looking at the over 2 million users of the Citibike program, about 65% of the users are men, and  81% of the users are subscribers to the program as opposed to casual customers. 

![Rider Topography](https://user-images.githubusercontent.com/84881187/132613986-5aefff38-7399-4275-9194-e3fd445a79ce.PNG)


According to the [US Census Bureau](https://www.census.gov/quickfacts/fact/table/newyorkcitynewyork,desmoinescityiowa/PST045219) the gender ratios in NYC are similar to those in Des Moines Iowa. In July of 2019, Des Moines was comprised of roughly 50.7% female, where NYC was 52.3% female. This could indicate that there could be similar trends based on gender demographics alone. In New York City, the highest density of Top Starting and Top Ending locations for Citibike trips occur most frequently in mid-town Manhattan. The highest density trips also correlate to popular tourist locations; as well as popular hotel locations. 

![Location Density](https://user-images.githubusercontent.com/84881187/132614892-7ddec200-ce2b-4178-a132-aa8b09f66bb0.PNG)


When we look at the length of time for each bike rental, along with the number of rentals, we see that the majority of rentals are less than 30 minutes. This indicates that it would be in the best interest of the bikesharing service to invest in a large quanity of bikes upon initial release to meet the demand of the potential users.

![Checkout Times](https://user-images.githubusercontent.com/84881187/132615718-fb5e2bd5-0d85-44a7-ae23-7c7d58a3b991.PNG)


Looking at the Checkout Times by Gender, we see a similar trend to to the user population. Males make us a majority of users and tend to take slightly longer trips. 


Looking at our Trips by Dat of the Week graph, we see that Thursday has significantly more users than any other day of the week. 

![Trips by Day](https://user-images.githubusercontent.com/84881187/132772132-e0a91e71-7abc-4203-ab80-2b873283be0f.PNG)

When we examine our Peak Hours for the month of August, 2019, we can observe that the highest number of users is during 5pm - 7pm


When we join this data, our Trips By Hour chart shows that Thursdays at 5pm - 6pm definitely have the highest density of users on the road.

![Trip By Hour](https://user-images.githubusercontent.com/84881187/132772522-14587e36-43e2-46d2-99d0-0f41d33bd86a.PNG)

Looking at our Trips by Weekday Topography chart, we can see that the majority of users during those Thursday rush-hours are primarily Male Users that are subscribers to the service. This could indicate that a significant number of the users are not only tourists, but business men, local to the area, using the service on a regular basis.

![Trip by Weekday topography](https://user-images.githubusercontent.com/84881187/132772626-307580e6-55b2-47ab-9c5a-93bca8fc1098.PNG)


