# Bike-sharing Program in Des Moines
## Background
To put together a solid business proposal for Des Moines Iowa on a bike-sharing business, a data set for New York city was leveraged to gain insights to consumer behavior.  Insights of trip duration and usage times throughout the week for different consumers for the month of August in 2019 was used.

# Analysis
## Deliverable 1 
The NY City bike data source needs the trip duration converted to a datetime format for our usage in Tableau.  A Jupyter Notebook NYC_CitiBike_Challenge.ipynb was leveraged to import the data set file 2019-08-citibike-tripdata.csv, add the desired trip duration field of datetime format, and then save that out as a new file named citbike_data.csv.

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliverable1_tripduration_datetime.png)

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/citibike_df_head_image.PNG)

## Deliverable 2
Key insights of the bike data can be interactively explored at: [NY CitiBike Challenge Deliverable 2 Analysis](https://public.tableau.com/app/profile/jonathan.jones5342/viz/NYCBikeChallengeDeliverable2/NYCitiBikeChallengeDeliverable2Analysis?publish=yes). In summary the following keypoints can be made for each image.

* For the question of how long the bikes were checked out for all riders and gender, we can see in the VIZ that most checkout times are less than 30mins.  Additionally, the bike trips for males were the majority and longest.

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_checkout_times_for_users.PNG)

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_checkout_times_for_users_gender.PNG)

* In the following two visualizations it shows that clear commuting usage with times of around 8AM and 5PM exists.  It is also clear that the majority of these commuters are male.

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_tripsbyweekday_byhr.PNG)

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_tripsbyweekday_byhr_bygender.PNG)

* Lastly, it is clear that with the visualization below that male subscribers are likely to use the bikes every day of the week.  While the non-subscribers are more likely to use the bikes on the weekends.

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_tripsbygender_byweekday.PNG)

## Deliverable 3
Using the NY City bike data some conclusions for the Des Moines bike-share program can be made.  Key insights of the bike data can be interactively explored at: [NY CitiBike Challenge Deliverable 3 Analysis](https://public.tableau.com/app/profile/jonathan.jones5342/viz/Bike-SharingAnalysisChallengeDeliverable3/NYCitiBikeChallengeStory?publish=yes). In summary the following keypoints can be made for each image.

* Largest gender group is male with subscribers having the most trips. Subscription programs should consider discounts for households to potentially increase female subscribers.  To increase non-subscriber usage consider weekend discounts.

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/piecharts.PNG)

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_tripsbygender_byweekday.PNG)

* Des Moines' commuting needs would have to be evaluated for the bike-sharing as well as bike-sharing stations near public transit areas. 

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/commutingandages.PNG)

* Using the below trip times combined with gender the populations of Des Moines an estimate to the number of bikes needed could be made.

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_checkout_times_for_users.PNG)

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_checkout_times_for_users_gender.PNG)

* Likewise the below visualizations indicate that understanding the commuter usage will determine the bikes required at peak times of 8AM and 5PM.

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_tripsbyweekday_byhr.PNG)

![alt text](https://github.com/jj2773/bikesharing/blob/main/images/deliv2_tripsbyweekday_byhr_bygender.PNG)

# Summary
It is imperative to understand the commuting need for bikes in Des Moines as this is the NY City bike's largest usage.  Locations of the bike-sharing stations should be near public transits and parks.  Two additional visualizations that should be considered are:
* The percentage of bikes used for each day of the week to enable discounting to increase usage.
* The percent of bike trips in 20 min increments by day to better estimate the number of bikes needed.