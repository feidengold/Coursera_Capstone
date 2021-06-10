## Battle of the Neighborhoods - Capstone Project
### Introduction 
New York City is one of the most famous, romantisized and desired city for living in the world due to its image portraid in the pop culture. A few would expect that behind the luxurious image of movie-like apartment buildings there is a sad reality of absense of simple necessities like washing machines and drier inside an apartment and at times even within the building. A large population of NYC is utilizing public laundromats to do their laundry.

Due to a high demand and low maintenance requirement, laundromat business is a great opportunity to generate steady cash flow for the business owner in NYC. This is why our client has decided to invest into opening a laundromat in NYC and asked for analysis of the best location for his new business. Based on the business type and for the sake of this capstone project, our simplified assumptions for the best location would be a high density population area with a low number of laundromats.

### Data
Data required to approach the above business case should include: New York City neighborhoods and boroughs geographical locations (latitude, longitude), laundromats locations and boroughs population density.

New York City data containing the neighborhoods and boroughs latitudes and longitudes can be obtained from https://cocl.us/new_york_dataset. While FourSquare API will be used to obtain data on existing laundromats. Population density data per each borough will be extracted from http://www.demographia.com/dm-nyc.htm.

## Methodology
After collecting the data from https://cocl.us/new_york_dataset it will be wrangled into a dataframe format. Using the density data from http://www.demographia.com/dm-nyc.htm all above average density boroughs will be mapped onto the map. Then using Foursquare we will locate all venues in the following boroughs and then filter by "laundromat" or "laundry" locations. Finally, the data be will be visually assessed fromthe resulted map.

## Business Problem
What is the best location(s) for laundromat in New York City?
In what Neighborhood and/or borough is preferred for investing into laundromat business?
