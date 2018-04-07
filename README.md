# project2_NYCfire

Tasks
1. Location of Severe Fires

Provide a leaflet map of the severe fires contained in the file severe_incidents.csv. Ignore locations that fall outside the five boroughs of New York City. Provide at least three pieces of information on the incident in a popup.

2. Layers and Clusters

a) Color by Type of Property

Start with the previous map. Now, distinguish the markers of the fire locations by PROPERTY_USE_DESC, i.e. what kind of property was affected. If there are too many categories, collapse some categories. Choose an appropriate coloring scheme to map the locations by type of affected property. Add a legend informing the user about the color scheme. Also make sure that the information about the type of affected property is now contained in the popup information. Show this map.

b) Cluster

Add marker clustering, so that zooming in will reveal the individual locations but the zoomed out map only shows the clusters. Show the map with clusters.

3. Fire Houses

The second data file contains the locations of the 218 firehouses in New York City. Start with the non-clustered map (2b) and now adjust the size of the circle markers by severity (TOTAL_INCIDENT_DURATION or UNITS_ONSCENE seem plausible options). More severe incidents should have larger circles on the map. On the map, also add the locations of the fire houses. Add two layers (“Incidents”, “Firehouses”) that allow the user to select which information to show.

4. Distance from Firehouse and Response Time

We now want to investigate whether the distance of the incident from the nearest firehouse varies across the city.

a) Calculate Distance

For all incident locations, identify the nearest firehouse and calculate the distance between the firehouse and the incident location. Provide a scatter plot showing the time until the first engine arrived (the variables INCIDENT_DATE_TIME and ARRIVAL_DATE_TIME) will be helpful.

b) Map of Response Times

Provide a map visualization of response times. Feel free to differentiate by incident type / property affected.

