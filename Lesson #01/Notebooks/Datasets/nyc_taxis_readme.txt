# NYC Taxi Trip Data


Source: [NYC Taxi and Limousine Commission](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml)


This data set includes a 1/50th random sample of all trips between January and June 2016 that either start or end at an aiport location.


## Column Summary


- `pickup_year` - The year of the trip.
- `pickup_month` - The month of the trip (January is `1`, December is `12`).
- `pickup_day` - The day of the month of the trip.
- `pickup_dayofweek` - The day of the week (Monday is `1`, Sunday is `7`)
- `pickup_time` - The time that the trip started, as one of six categories:
    - `0` - 0:00am-3:59am.
    - `1` - 4:00am-7:59am.
    - `2` - 8:00am-11:59am.
    - `3` - 12:00pm-3:59pm.
    - `4` - 4:00pm-7:59pm.
    - `5` - 8:00pm-11:59pm.
- `pickup_location_code` - The airport or [borough](https://en.wikipedia.org/wiki/Boroughs_of_New_York_City) where the the trip started, as one of eight categories:
    - `0` - Bronx.
    - `1` - Brooklyn.
    - `2` - JFK Airport.
    - `3` - LaGuardia Airport.
    - `4` - Manhattan.
    - `5` - Newark Airport.
    - `6` - Queens.
    - `7` - Staten Island.
- `dropoff_location_code` - The airport or borough where the the trip finished, using the same eight category codes as `pickup_location_code`.
- `trip_distance` - The distance of the trip in miles.
- `trip_length` - The length of the trip in seconds.
- `fare_amount` - The base fare of the trip, in dollars.
- `fees_amount` - Any fees added to the fare, eg surcharges, extras, and MTA taxes.
- `tolls_amount` - The amount of all tolls paid during the trip.
- `tip_amount` - The tip added by the customer - does not include cash tips.
- `total_amount` - The total amount charged to the passenger, excluding cash tips.
- `payment_type` - The payment type, one of six categories:
    - `1` - Credit card.
    - `2` - Cash.
    - `3` - No charge.
    - `4` - Dispute.
    - `5` - Unknown.
    - `6` - Voided trip.