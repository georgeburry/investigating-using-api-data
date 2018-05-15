# Investigating crashes using API data

A number of factors can increase the chances of a car crash occuring - for instance: weather, drink-driving or time of day. In this in project, I set out to collect data from the web in order to understand the circumstances surrounding car crashes in the state of Maryland, U.S. The crash data was taken from the U.S. website: data.gov.

First of all, the Foursquare API is used to collect data about the number of bars within in a certain radius in each County, in order to see if the prevalence of drinking might have an influence on the accident rate.
Second of all, the Google Maps API is used to determine the coordinates of each county, then the coordinates are used to request the weather conditions at the time of the accident from the DarkSky API.
Finally, the coordinates of the accidents themselves are obtained and plotted on a map using the Google Map Plotter.

## Data

The data for this exercise can be found [here](https://catalog.data.gov/dataset/2012-vehicle-collisions-investigated-by-state-police-4fcd0/resource/d84f79b6-419c-49e0-a74c-01b34a9575f2).
