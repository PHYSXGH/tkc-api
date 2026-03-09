# The interstellar route planner API spec

This page contains the API spec for the interstellar route planner in the form of a static github page.

I have decided to somewhat amend some of the endpoints, the details of which are below:

- GET /transport/{distance}?passengers={number}&parking={days} returns three values, each of the teo options adn the lower of the two. I think this would allow people to better compare the options.
