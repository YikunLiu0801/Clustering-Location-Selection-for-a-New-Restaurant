# The-Battle-Of-Neighborhoods
## Introduction
A client is looking for a good neighborhood to open a new restaurant in the city of Toronto. This project helps this client to analyze neighborhoods and find a best one for a new restaurant with DBSCAN clustering method in Python. The best neighborhood is selected based on the numbers, the diveristy, and the average ratings of the existing restaurants in this neighborhood. A neighborhood with medium number of low-diversity, low-rating restaurants will be identified as a promising business opportunity.

## Data Sources
1. A webpage containing basic neighborhood information of Toronto
https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

The extracted data will have 3 columns:
- Postal Code
- Borough
- Neighborhood

2. Coordinates of these neighborhoods from Google API

The refined data will have 5 columns:
- Postal Code
- Borough
- Neighborhood
- Latitude
- Longitude

3. Venues' categories around these neighborhoods from Foursquare API

The final data will have 8 columns:
- Postal Code
- Borough
- Neighborhood
- Latitude
- Longitude
- Restaurant Counts
- Restaurant Diversity
- Cluster

