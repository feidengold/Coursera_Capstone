## Battle of the Neighborhoods - Capstone Project
### Introduction 
New York City is one of the most famous, romanticized and desired cities for living in the world due to its image portrayed in the pop culture. Some of the worlds' most popular content creators and influencers are located in the city for its stunning backgrounds and instagrammable dining and coffee locations. Combining that with the overall growing trend for coffee and small business coffee shops makes it an attractive investment to open a new coffee shop specifically in NYC where this coffee shop is likely to receive a lot of attention on social media to drive revenue.

Based on the business type and for the sake of this capstone project, our simplified assumptions for the best location would be a high-density population area with a relatively low number of existing coffee shops. Existing competition might in reality be a good factor as a specific neighborhood could be famous for its coffee shops and would attract more customers. In this project, we will examine the landscape of the city on existing competition to identify the best location for the investment.

### Data
Data required to approach the above business case should include New York City neighborhoods' and boroughs' geographical locations (latitude, longitude), coffee shops' locations and boroughs' population density.

New York City data containing the neighborhoods and boroughs latitudes and longitudes can be obtained from https://cocl.us/new_york_dataset. While FourSquare API will be used to obtain data on existing coffee shops. Population density data per each borough will be extracted from http://www.demographia.com/dm-nyc.htm.

## Methodology
After collecting the data from https://cocl.us/new_york_dataset it will be wrangled into a dataframe format. Using the density data from http://www.demographia.com/dm-nyc.htm all above average density boroughs will be mapped onto the map. Then using Foursquare we will locate all venues in the following boroughs and then filter by "coffee shop" locations. Finally, the data be will be visually assessed from the resulted map.

## Business Problem
What is the best location(s) for coffee in New York City?
In what Neighborhood and/or borough is preferred for investing into coffee shop business?
What (if any) neighborhood is a to-go-to for a cup of coffee?
