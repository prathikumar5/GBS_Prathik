Implementation Details:

1. Load the map using rest api shared(http://services.arcgis.com/XTtANUDT8Va4DLwI/arcgis/rest/services/NZBrewLocation/FeatureServer/0)
2. Add Scale bar and home button(default view)
3. Add Search option to serach to address
4. Add Find the Beer button: which on click will take to Deep Creek Brewery with zoom
	Note: Double click / Click Again (twice) to show the legend
5. Add Breweries in New Zealand widget: List breweries to selectin drop down
6. Click to brewery will zoom to location
	Note: Double click / Click Again (twice) to show the legend
7. Created developer account for ArcGIS (http://prathik-kumar.maps.arcgis.com/home/item.html?id=019357d0496243408306a99e71bfef2d)
All the feature are added in NzBreweries.html 

Time taken:

Understanding Concepts (ArcGIS - API) : 4-5hrs
Development: 2-3hrs
Testing: 1hr

Issues faced:

1. Only single click was not able to load zoom with legend. Was getting JScript error (Cannot read property 'type' of null
 at k.get [as isPolygonMarkerSymbol] js.arcgis.com/4.3/esri/views/MapView.js:408) but on double click it loads the legend.
2. Loading list of breweries in NZ : Tried using request to get the details of mao and find all breweries using the json, but was unable to find the details.
Hence I have harcoded the list of breweries to select and find them passing the objectid.
3. Widget development : Have installed Node/Dojo/TypeScript to run ts file to generate js and load the same to widget, but was unable to load the widget with details.
4. Tried to host the widget in my developer account, but was unable to added layers as I couldnt generate GeoJson or CSV file with details of the task.



Conclusion:

Its really amazing, challenging and intersting working with these objects ans services.
I have tried to my best to undestanding the various features of ArcGIS and tried couple of test cases to get best results.
I was stuck at few places, but with lil more understanding on widget/ArcGIS/Layers and other modules, I should be able to acheive what I need.

