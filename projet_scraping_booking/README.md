# Plan your trip

### requirements

- Install python3
- Install sklearn, pandas, numpy, plotly, scrapy


### Goal


## Scrape data from destinations
- Get weather data from each destination
- Get hotels' info about each destination


## Get weather data with an API
- Use https://nominatim.org/ to get the gps coordinates of all the cities (no subscription required) Documentation : https://nominatim.org/release-docs/develop/api/Search/

- Use https://openweathermap.org/appid (you have to subscribe to get a free apikey) and https://openweathermap.org/api/one-call-api to get some information about the weather for the 35 cities and put it in a DataFrame

- Determine the list of cities where the weather will be the nicest within the next 7 days For example, you can use the values of daily.pop and daily.rain to compute the expected volume of rain within the next 7 days... But it's only an example, actually you can have different opinions on a what a nice weather would be like 😎 Maybe the most important criterion for you is the temperature or humidity, so feel free to change the rules !

## Scrape Booking.com
Since BookingHoldings doesn't have aggregated databases, it will be much faster to scrape data directly from booking.com

You can scrap as many information asyou want, but we suggest that you get at least:

- hotel name,
- Url to its booking.com page,
- Its coordinates: latitude and longitude
- Score given by the website users
- Text description of the hotel

## Deliverable
Two maps with a Top-5 destinations and a Top-20 hotels in the area.


