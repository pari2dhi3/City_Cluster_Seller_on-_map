City Cluster Seller Visualisation

Aim:
To visualise the operational cities of Shadowfax in India and to show the clusters in each city and further showing sellers in each cluster on maps.

Description:
Using The Google Maps Geolocation API, the operational cities are marked using marker and while mouse hovering, a pop-up window is displayed showing City, Lat Lng and Cluster count of respective city. On mouse-click on these markers, the map pans to that city and shows clusters. 
The clusters are marked as circles with center as cluster center and radius = Number of orders of a particular cluster * 12 (scaling factor). While mouse hovering on these circles, a pop-up window is displayed showing Cluster name, Cluster Id, Lat Lng, Seller Count within that cluster, Order Count = sum of orders in the month of May in that cluster. 
On mouse-click on these circles, the map pans to that cluster and shows sellers by markers. While mouse hovering on these markers, a pop-up window is displayed showing Seller name, Seller Id, Lat Lng, Order Count = sum of orders in the month of May by that seller. 
To zoom out to city level, double-click on any of the marker representing seller and to zoom out to country level, double-click on the marker representing city. 
The data like city, cluster name, cluster id, cluster center lat lng, seller name, seller id, seller lat lng, order count by that seller is extracted from level1.json.
