# Overview (NYC_Yellow_taxi_demand_prediction)

## Summary
This is Data set is provided by NYC Taxi & Limousine which is aimed to predict taxi demand in new york city.

## Source of Dataset used
New York City Taxi Trip Data (2013)
Source: NYC Taxi & Limousine Commission

## Data Dictionary
### yellow_tripdata_2013_jan.csv
  * vendor_id:  e.g., Verifone Transportation Systems (VTS), or Mobile Knowledge Systems Inc (CMT), implemented as part of the Technology Passenger Enhancements Project.
  * rate_code: taximeter rate. Check http://www.nyc.gov/html/tlc/html/passenger/taxicab_rate.shtml.
  * pickup_datetime: start time of the trip, mm-dd-yyyy hh24:mm:ss EDT.
  * dropoff_datetime: end time of the trip, mm-dd-yyyy hh24:mm:ss EDT.
  * passenger_count: number of passengers on the trip, default value is one.
  * trip_distance: trip distance measured by the taximeter in miles.
  * pickup_longitude and pickup_latitude: GPS coordinates at the start of the trip.
  * dropoff_longitude and dropoff_latitude: GPS coordinates at the end of the trip.
  * payment_type: cash or credit card.
  * fare_amount: the meter fare, it should include the Newark surcharge, in USD.
  * surcharge: extra fees, such as rush hour and overnight surcharges, in USD.
  * mta_tax: metropolitan commuter transportation mobility tax, in USD.
  * tip_amount: tip amount (for credit card transactions only), in USD.
  * tolls_amount: total price paid for tolls, summed across all tolls for the trip, in USD.
  * total_amount: all charges that are presented to the passenger at time of fare payment (includes tip for non-cash trips), in USD.

### TERMS
  * medallion: a permit to operate a yellow taxi cab in New York City, it is effectively a (randomly assigned) car ID.
  * hack_license: a license to drive the vehicle, it is effectively a (randomly assigned) driver ID.
  
## Sampling
Randomly selected 1,000 medallions from January 2013 and extracted all of their trips throughout the year.
