# (Communicate Data findings)
## by Oluwafemi OLUWASINA


## Dataset
>The datasets I chose for this project are 5 in number which includes the ford Go Bike System Data from San Francisco Bay Area, The Divvy Trips from Chicago, Illinois, The Citibike Trip data from New York City, The Capital Bike Share trip data from washington Dc Metro Area and the Cogo trip data from Columbus,Ohio.
The first step i took in wrangling involves tiding up of each of the datasets which involves renaming the columns to make sure they are uniform  and ready fro merging. I also made some changes in the datatypes of some columns to make sure all datsets are uniform.
Some null values were discovered and dropped accordingly. some additional columns were added which include distance covered with the coordinates which was derived using the pyproj Library.
Also, Speed (Distance/Trip duration) Column was added. Age column was also added. After this, some null and duplicate values were discovered and were dropped. 
Age exceeding 70 years was dropped because it seems not logical for riders Older than 70 to participate in such trips.

## Summary of Findings
>In the Dataset combined, I observed some informations were needed like the distance, speed, Age etc, I had to Some locations preferred a user-type to another and would only go in that direction. The youngest was 13 years old from New york city, while the Oldest rider is 69 years old also from New york city. A 33 year old Female from San Francisco Bay area was the fastest rider of 10m/s. These presentation will be included in the explanatory presentation.

## Key Insights for Presentation
> The male gender of the Subscriber user type and Age around 33years is seen to cover the highest distance of more than 15,000 metres, while for the Customer User typeThe Male gender was also with the highest distance covered of above 15000metres also about 33 years of age.
>Riders of other gender are seen to be less dominant in the teenagers and riders in their 60s as seen in the rest of the Age category. The Male and Female genders are seen to be most dominant in all, while the male gender is seen to have attained the highest speed of 8m/s.
>It was noticed that the riders with age 50 years tarried most in the ride recorded as the other gender while the male and female came second and third respectively.
