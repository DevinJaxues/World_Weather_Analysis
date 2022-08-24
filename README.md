# World Weather Analysis
## Devin Monsen
### 08/24/2022
---
**Weather Database**
---
<sub> Simply here were just practicing API pulls and cleaning the data into a useable dataframe. Using the OpenWeather API we got a set of coordinates then retreived our city_data dataframe. Then after organizing the columns we save our data to a CSV to use in our Vacation_Search and Vacation_Itinerary.</sub>
---
**Vacation Search**
---
<sub> First we pulled our dataframe from the Weather Database. Created a user input to creater a preferred city dataframe for vacation options. Called to a google API to match our hotel names and put this into our WeatherPy_vacation.csv. And lastly used our columns in the dataframe to create a gmaps figure to display our options that match our users preference.</sub>
---
**Vacation Itinerary**
---
Unfortunately I ran into some issues here. I know our purpose was to call up the Vacation Search and choose 3 locations to stop and provide a route from point A to B to C to D and back to A. Ran into some index errors on creating the tuples for the vacation start, end, stop1, stop2, and stop3. This disabled me from being able to create the figure sadly, so i cant tell if that code would've worked.</sub>
