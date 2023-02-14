# (Ford GoBike System Data)

## by (Qasem M Dhamad)



# Ford GoBike System Data Exploration

## Dataset

The data consists of information regarding "183412" rides made in a bike-sharing system covering the greater San Francisco Bay area, including uration_sec', 'start_time', 'end_time', 'start_station_id', 'user_type, and other features.The dataset was provided by Udacity.

## Summary of Findings


In the exploration, it seems reasonable that bike sharing is only available to subscribers. The majority of members are 20-40 year old males who are subscribers and did not share the bike for the entire ride. The majority of travels take less than 1000 seconds, while only a few take more than 2000 seconds. Members that are younger are more likely to share the bike.! In addition, user type does not affect age-duration relationships. Males have shorter trips than other genders. However,bike sharing is inversely related to ride time for all trips. 

Outside of the main variables of interest, I verified the relationship between
ridesharing time and user gender. For the dataset given,most bike-sharing customers are men, while less than half are women and a very small number of cyclists are unsure of their gender. It also proves that male consumers spend the most time using carpooling services!




## Key Insights for Presentation


For the presentation, I focus on just the influence of the user type. I start by introducing the age distribution, followed by the distribution of trip duration, then plot the transformed scatterplot as well as plotting the user type count or frequency for member_gender.

Next, I introduce categorical variables one by one. Begin,
I use violinplot of age, gender, and bike sharing. The other categorical
variables, bike_share_for_all_trip and age, are covered afterwards, using boxplot. I used a different color palette for each quality variable to make it different for each plot.
