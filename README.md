# The interstellar route planner API spec

This page contains the API spec for the interstellar route planner in the form of a static github page.

I have decided to somewhat amend some of the endpoints, the details of which are below:

- GET /transport/{distance}?passengers={number}&parking={days} 
returns three values, each of the teo options and the lower of the two. I think this would allow people to better compare the options.
- GET: /gates/{gateCode}/to/{targetGateCode}?round_trip={true|false}
has the additional round_trip query string attached permanently and is now one endpoint, as it just makes more sense. If the return distance isn't required, the field is not present in the response.