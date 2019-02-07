# Lab-1-Web-mapping
Here is the first GEOB472 lab -- Web mapping

## Crime rate in the City of Vancouver
<img width="939" alt="crime" src="https://user-images.githubusercontent.com/46465672/52376772-d05ed100-2a17-11e9-8840-17aec5fdbbd8.png">

## Reflective analysis

### Data choice and purpose
In Vancouver, crime rates are closely related to people's normal lives, and everyone wants to be safe in their living environment. The purpose of this map is to show the crime rate and the number of “break and entry” to provide useful information and remind people to increase their safety awareness. I collected crime data from the Vancouver Open Data Catalogue in 2019. These data provide useful information about specific levels of security and help raise community awareness of Vancouver police activities. I downloaded the crime data as a zipped shapefile and imported it to the Mapbox tailsets. Mapbox system will transfer the raw data to the vector data as it is uploaded and processed. Moreover, this data can be also use to analysis the relationship between housing price and criminal rate. The outcome can provide useful information for the potential house buyer so that they can choose the location of their house and let the housing property re-evaluate the housing price.
### Context
The visualization of the map shown above is a heat map. Red indicates high crime rates and high-density areas, mainly concentrated in the eastern part of downtown Vancouver and near East Vancouver and Burnaby. Kitsilano, Point Grey and other areas in Vancouver's West End and near UBC have relatively low crime rates.
### Cartography and map design
I divided the crime data set into six density ranges (0, 0.1, 0.2, 0.3, 0.5, 0.7, 1.0) and set different colors using the 20px heat map radius. In addition, when a heat map of approximately 16-20 is placed, the urban building will be displayed on the map indicating the exactly geographic location of housing break and entry. I highlighted the primary road to indicated the geographical coordinate within the city of Vancouver. Besides, change the color of national park because the forest as an important factor address the city's environment. In order to improve this map, I would like to add more dataset such as locational information of policy station, population in private household, etc. 

##### Link to the map

https://api.mapbox.com/styles/v1/vikkijiang/cjrt3lq2g0iti1fsxvzk42691.html?fresh=true&title=true&access_token=pk.eyJ1Ijoidmlra2lqaWFuZyIsImEiOiJjanJsMmppdTgwNDRxNDRwbDRjNjlvajVxIn0.JhszGejK6QMx3OGEJbSjyQ#11.3/49.248390/-123.127782/0

### Critique
The results of the map can provide useful information to Vancouver residents and increase safety awareness. Understanding the process that leads to this discontinuity is an important issue for future research, namely the crime rate of “breaking through and entering the family”. There are many errors, and some aspects do not involve research analysis such as population density. I want to add to the location of the police station, which may affect the crime rate. From the perspective of geographic mapping, there are some missing information, such as legends, brief backgrounds of the thesis for this map.
