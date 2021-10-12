# Ford Go-Bike (Data Visualization project)

## Dataset

The data consists of information regarding 183,412 entries of ride bikes,with 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude','start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type','member_birth_year', 'member_gender', 'bike_share_for_all_trip'). Most variables are numeric in nature, but the variables member_gender and bike_share_for_all_trip are both categorical (nominal variables).
You can get the data from here : https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv


## Summary of Findings

The relation between age and velocity didn't show any linear correlation. When we grow up the average velocity increases till the age of 37 then it decreases when we get older. Plots showed that men are faster than women on average (not significantly). But the fastest among the bikers were women. The velocity is normally distrubted. Most of the subscribers (90.5%) doesn't share there bikes. The bikers who doesn't share there bikes tends to be faster than those who doesn't.


## Key Insights for Presentation

For the presentation,I've started with the univariate plots then bivariate and finishing with the multivariate plots. Then I've polished all the plots to be clear. I've mainly focused on the influence gender and the age with the average of velocity. I've used many kind of plots but the line plots was the best one since there were a lot of data points in small area.

Afterwards, I've introduced two categorical variables which are user type and bike share. I've used clustered bar charts to show the interactions between these variables together. 

Please note the output_toggle.tpl didn't work with me(due to the nbconvert version) so I removed all the code cells from the presentation instead.
