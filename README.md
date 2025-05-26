# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Compare results from two different API's and produce a regression model for variables of your choice.

## Process
### Call city bikes API for bike stations in Toronto
### Parse those results into a dataframe
### Call Foursquare(FSQ) API for the bike stations obtained in part 1
### Filter for the category restaurants, and parse the results into a dataframe
### Call Yelp API for the bike stations obtained in part 1
### Join FSQ and Yelp data into dataframe
### Provide visualizations for the EDA
### Add all results into SQLite3 database
### Produced regression model

## Results
Yelp API provided more complete data compared to FSQ API. 

## Challenges 
I waited until the end to run all the API calls. When I tried to join the 2, my laptop crashed. So I tried again two times and as a result my Yelp API calls ran out for the day. Therefore, some results are missing. However, the code is all there. I will rerun this when the calls refresh.

## Future Goals
Explore more categories in the API calls and produce a multivariate regression model. 
