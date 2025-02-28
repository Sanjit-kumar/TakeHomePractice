Given this Open Weather Geocoding API (https://openweathermap.org/api/geocoding-api),
please write a utility that takes a city, state, or zip code and returns the latitude, longitude, place
name, and any other necessary information from the API. Your utility should make use of the
Coordinates by location name and the Coordinates by zip/post code endpoints. Your program
should also be able to handle multiple location inputs

In the event that multiple locations are returned by the API, you can use the first result in the list
of returned locations.
Example Inputs
Inputs will be given in the following formats:
● City and place combination: “Madison, WI”
● Zip Codes: “12345”
Inputs should be given to the utility as a list of strings and should be able to handle multiple
locations of either city/state or zip location type at once
