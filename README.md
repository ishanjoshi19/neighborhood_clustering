# Neighborhood Clustering
##         Clustering the neighborhoods of Paris

### Business Problem

Paris is one of the top tourist destinations in the world. This project will cluster the neighbourhoods in Paris which will help tourists in choosing their destinations enhancing their experience. 

### Data Used

The data will be derived from 2 resources:
- **Paris data**:
We will use the JSON data available at https://www.data.gouv.fr/fr/datasets/r/e88c6fda-1d09-42a0-a069-606d3259114e

The following columns from this JSON file will be used:
1. postal_code: Postal codes
2. nom_comm: Name of neighbourhoods
3. nom_dept: Name of the borroughs
4. geo_point_2d: Tuple having longitude and latitude


- **Foursquare API**:
Foursquare is a location data provider with information about venues like name, location, menus etc within a defined area of interest. 

The data derived from the API call will provide us with:
1. Neighbourhood : Name of the Neighbourhood
2. Neighbourhood Latitude : Latitude of the Neighbourhood
3. Neighbourhood Longitude : Longitude of the Neighbourhood
4. Venue: Name of the Venue
5. Venue Latitude: Latitude of Venue6. 
6. Venue Longitude: Longitude of Venue
7. Venue Category: Category of Venue
 
We will cluster the neighbourhoods based on similar venue categories.




