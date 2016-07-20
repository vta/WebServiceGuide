****
###Navigation

![Navigation](https://github.com/vta/WebServiceGuide/blob/master/Images/Navigation/Navigation.PNG)  

This toolbar contains the basic tools used for navigating a map.

* **Home:** Takes you to the home pane that shows information about the site.

* **Identify:** Select either by clicking a point or dragging a rectangle to select data on the map.  Can also enable buffering to add a buffer before you make a selection. This will then select all features within the area you select plus the buffer.  The ability to select what layers you want to identify is also available.  Useful for when you want to view layers on the map, but don't want them included in your selection.

* **Pan:** Tool to pan the map.

* **Zoom In/Out:** Select an area to zoom in and out from.  Can also double click map to zoom in or use roller on mouse.

* **Full Extent:** Zooms to full extent of map. (World View)

* **Previous Extent/Next Extent:** Similar to back and forward history buttons in browser.  Takes you back to the previous map view or takes you forward to the next map view if you went back.

* **Bookmarks:** Takes you to preset map extents or you can add your own.


****
###Tasks

![Tasks](https://github.com/vta/WebServiceGuide/blob/master/Images/Tasks/Tasks.PNG)

This toolbar contains the tools for sharing, printing, exporting, or adding data to the map.


* **Print:** ![printtasks](https://github.com/vta/WebServiceGuide/blob/master/Images/Tasks/Tasks_Print.PNG)  
Opens the print dialog for creating the print template with legend. The template allows you to choose the page size, output format, resolution (96 dpi, 300 dpi), and map scale.  You can also add a title to the top of the page and notes that will show in the bottom right hand section of the page.  Unclick the "Lock print preview with map" to be able to adjust what area on the map you would like to print.  Click print for the file to be created.

* **Export:** Allows you to export just the map view as either a PNG, BMP, JPEG, TIFF, GeoTIFF, or PDF.  You can also include georeference data to make the image georeferenced.  This will allow you to add it to ArcMap or Google Earth and it will show up in the correct geographic location.  This tool does not include a legend or any other data.  Just the map view. 

* **Share**: Opens a dialog to share the link via social media or email.  It will not share any drawings you have added, but it will share if zoomed in on a specific area.

* **Upload:** This tool lets you upload csv, xlsx, kml, shp, gpx, or zip files containing geodatabases or shapefiles.  This will temporarily add the layer to the map for you to view.  Once the map is closed and re-opened that added shape will disappear.

****
###Analysis

![Analysis](https://github.com/vta/WebServiceGuide/blob/master/Images/Analysis/Analysis.PNG)

This toolbar allows you to perform measuring functions and draw/export drawings from the map.


* **Advanced Measuring:**  
![Measuring](https://github.com/vta/WebServiceGuide/blob/master/Images/Analysis/Analysis_Measuring.PNG)  
This tools gives you the option to measure by line, freehand line, freehand shape, ellipse, circle, polygon, or rectangle.  Once one of these is selected the toolbar will expand to show the option of what measurement unit to use.  The top unit is the distance measurement and the bottom box is the area measurement unit.  To snap to certain features, click the enable snapping button then the Select Snapping Layers to select which layers to snap to.  When you perform the measurement on the map, it will show the line or shape with the measurements labeled on the map.  To remove the measurements from the map, click the Edit drop down arrow and select clear.  You can also export the line or shape to a new shapefile by clicking Export Drawings.

* **Edit Drawings:**  
![Draw Edit](https://github.com/vta/WebServiceGuide/blob/master/Images/Analysis/Analysis_Draw_Edit.PNG)  
These tools are used once a drawing has been added to the map.  Edit gives you the option of editing the drawing shape, erasing part of the drawing, or clearing the drawing completely.  Export Drawings allows you to export the drawings to a shapefile.

* **Draw:**  
![Draw](https://github.com/vta/WebServiceGuide/blob/master/Images/Analysis/Analysis_Draw.PNG)  
This tool allows you to draw shapes on the map.  This includes points, text, lines, freehand line, freehand shape, ellipse, circle, polygon, or rectangle.  Once one of these are selected the Draw tool expands to show Snapping and Styles.  To snap to certain features, click the enable snapping button then the Select Snapping Layers to select which layers to snap to.  The Styles button opens a pop-up that gives you the option of choosing color and style for the drawing.

****

###Find Data

![Find Data](https://github.com/vta/WebServiceGuide/blob/master/Images/FindData/FindData.PNG)

This toolbar allows you to locate data on the map either by plotting coordinates, selecting by shape, query, or filter.


* **Plot Coordinates:**  
![Coordinates](https://github.com/vta/WebServiceGuide/blob/master/Images/FindData/FindData_Coordinates.PNG)  
This tool allows you to enter coordinates to plot on the map or click on the map to see the coordinates for that location. It gives you multiple format options in WGS84: lat/long (decimal degrees), degrees decimal minutes, degrees minutes seconds, or x/y.  Once coordinates are selected, to remove them from the map you can click the three dots next to the coordinates and select Delete.  You can also select Enable Snapping to snap to a layer then Select Snapping Layers to select which layers to snap to.

* **Locate Data:**  
![FindData](https://github.com/vta/WebServiceGuide/blob/master/Images/FindData/FindData_Rectangle_Buffer.PNG)  
This tools allows you to find data by point, freehand, line, polygon, or rectangle.  Once one of these is selected the toolbar expands to include buffering, snapping, and identifiable layers tools.  The buffer tool, when selected, allows you to specify a buffer distance around the area you select.  For example, if you select a point with a 50-foot buffer it will select all features within 50-feet of that point. To snap to certain features, click the enable snapping button then the Select Snapping Layers to select which layers to snap to.  The Identifiable Layers enables you to select which layers you want to search for on the map.  This is helpful to still view multiple layers, but only search on one layer.

* **Query:**  
![Query](https://github.com/vta/WebServiceGuide/blob/master/Images/FindData/FindData_Query.PNG)  
This tool allows you to perform a query on a selected data source.  This query is similar to an excel query.  First you select a data source/layer, then select the field to perform the query on and the value to query.  The option of providing a spatial filter within the current extent only performs the query in the current map view.  You can add multiple queries on one data source, but cannot query multiple data sources at once.

* **Filter:**  
![Filter](https://github.com/vta/WebServiceGuide/blob/master/Images/FindData/FindData_Filter.PNG)  
This tool is very similar to query except that it doesn't give you a results tab.  It simply filters the data and displays it on the map.  First you choose the data source/layer, the select the field to perform the filter on the and the value to filter. The option of providing a spatial filter within the current extent only performs the filter in the current map view.  Once you click filter it will only display the selected features on the map.  Make sure the layer you are selecting is turned on and in view.  

****
