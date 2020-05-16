# [Clustering] Location Selection for a New Restaurant
## Introduction
In this project we will try to find an optimal location for a restaurant. Specifically, this report will be targeted to stakeholders interested in opening a __restaurant__ in the city of __Toronto__. This project helps this client to analyze neighborhoods and find good ones for a new restaurant with __kmeans__ clustering method in Python. The best neighborhood is selected based on the numbers, the diveristy, and the distance to the city center of the existing restaurants in this neighborhood. A neighborhood close to city center with medium number of low-diversity restaurants will be identified as a promising business opportunity.

## Data Sources
1. A __webpage__ containing basic neighborhood information of Toronto
https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

The extracted data will have 2 columns:
- Postal Code
- Borough

2. Coordinates of these neighborhoods from File 'Geospatial_Coordinates.csv'

The refined data will have 4 columns:
- Postal Code
- Borough
- Latitude
- Longitude

3. Venues' categories around these neighborhoods from __Foursquare API__

The final data will have 8 columns:
- Postal Code
- Borough
- Latitude
- Longitude
- Restaurant Counts
- Restaurant Diversity
- Distance
- Cluster

## Further Discussion

The top 2 zones, M9B and M4E are promising zones. They are rather commercial neighborhoods with a lot of parks, shops, food stands, and restaurants, but existing restaurants are not totally diversified. People who wants to seek opportunities in food industry in this neighborhood can try restaurants other than Coffee Shops.

The result does not imply that those zones are actually optimal locations for a new restaurant! Purpose of this analysis was to only provide info on areas close to city center but not crowded with existing restaurants - it is entirely possible that there is a very good reason for small number of restaurants in any of those areas, reasons which would make them unsuitable for a new restaurant regardless of lack of competition in the area. Recommended zones should therefore be considered only as a starting point for more detailed analysis which could eventually result in location which has not only no nearby competition but also other factors taken into account and all other relevant conditions met.

Final decission on optimal restaurant location will be made by stakeholders based on specific characteristics of neighborhoods and locations in every recommended zone, taking into consideration additional factors like attractiveness of each location (proximity to park or water), levels of noise / proximity to major roads, real estate availability, prices, social and economic dynamics of every neighborhood etc.

