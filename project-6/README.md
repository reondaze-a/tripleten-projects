# Data Collection and Storage(SQL) : Zuber

I'll be working as an analyst for Zuber, a new ride-sharing company that's launching in Chicago. 
For the first 2 parts of the project I've used SQL.

## Goal
The task is to find patterns in the available information. I'll try to understand passenger preferences and the impact of external factors on rides.
Working with a database, I'll have to analyze data from competitors and test a hypothesis about the impact of weather on ride frequency.

## Hypothesis
- The average duration of rides stay the same on rainy Saturdays.

# Data description

A database with info on taxi rides in Chicago:

- neighborhoods table: data on city neighborhoods
  - name: name of the neighborhood
  - neighborhood_id: neighborhood code

-cabs table: data on taxis
  - cab_id: vehicle code
  - vehicle_id: the vehicle's technical ID
  - company_name: the company that owns the vehicle

- trips table: data on rides
  - trip_id: ride code
  - cab_id: code of the vehicle operating the ride
  - start_ts: date and time of the beginning of the ride (time rounded to the hour)
  - end_ts: date and time of the end of the ride (time rounded to the hour)
  - duration_seconds: ride duration in seconds
  - distance_miles: ride distance in miles
  - pickup_location_id: pickup neighborhood code
  - dropoff_location_id: dropoff neighborhood code

- weather_records table: data on weather
  - record_id: weather record code
  - ts: record date and time (time rounded to the hour)
  - temperature: temperature when the record was taken
  - description: brief description of weather conditions, e.g. "light rain" or "scattered clouds"
 
