# [US Airport](https://loweas.github.io/USairportsmap/)
## A Web-Map of Airports in the United States
This map shows how many airports are in each state in the the United States and if they have a control tower or not.

### Data:
* Airport data is collected from a shapefile from [Data.Gov][].
*  US-States boundary data is acquired from [Mike Bostock][] of [D3][].
*  Basemap shows geographic features choosen from [Leaflet Previews][].
*   Font Awesome was used for the symbol of the plane.

### Graticules:
Change the default to blue, font : Dosis and doubled the interval so there were not as many lines at the starting screen.

### Dynamic labels
Font chosen : [Anton](https://fonts.google.com/specimen/Anton
) 

### Clickable Item:
An interactive element is added to each location with information on the city and state in which the airport is located. To retrieve this infomation click on the airplane figure of interest.

### Legend
The legend is catogozied by color, providing information on how many airports are in each state. The color of plane symnbol indicates if there is a control tower or not.



### Added feature form leaflet :
Coordinates were also added to follow your mouse while it scolls the screen around on the screen. [leaflet.coordinates][]


### Acknowledgements
Credit for project concept to Prof Bo Zhao and the class [GEOG 571][].





[Data.Gov]: https://catalog.data.gov/dataset/usgs-small-scale-dataset-airports-of-the-united-states-201207-shapefile
[Mike Bostock]: https://bost.ocks.org/mike/
[D3]: https://d3js.org/
[Leaflet Previews]: https://leaflet-extras.github.io/leaflet-providers/preview/
[leaflet.coordinates]: https://github.com/MrMufflon/Leaflet.Coordinates
[GEOG 571]: https://github.com/jakobzhao/geog571
