PyClub 
*******
A set of exercises for PyClub.

Challenge 1
============
Take the Portland GTFS feed and compile data about its trips as a CSV file with the following columns:

- trip_id,
- direction_id,
- route_id,
- start_time: first departure time of the trip,
- end_time: last departure time of the trip,
- duration: duration of the trip in hours,
- start_stop_id: stop ID of the first stop of the trip,
- end_stop_id: stop ID of the last stop of the trip,
- num_stops: number of stops on trip,
- distance: distance travelled by the trip's vehicle in km,

Note that the Portland feed distances are in feet.

Suggestion: use Pandas. 

Challenge 2
============
Redo Challenge 1, but use the Brisbane feed, which has no distance data.  

Suggestion: use Shapely and utm to calculate distances.