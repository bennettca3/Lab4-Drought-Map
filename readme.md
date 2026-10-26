U.S. Drought Map, Week of October 13, 2026

An interactive web map showing how much of each U.S. state was in moderate drought for the week of October 13, built with Leaflet for GHY 5818 (Web Mapping) at Appalachian State University, Lab 4.

About this map

Each state is shaded by the total percentage of its area in moderate drought.  Darker colors mean more of the state in moderate drought.

Features:

Choropleth map: five classes on a sequential yellow-orange-red color ramp (ColorBrewer YlOrRd)
Hover: highlights a state and shows its name and total moderate drought percentage in the info panel.
Click: zooms to the selected state.
Legend: class ranges with units.
About panel: a short description of the map and its data.

Data: 

Drought Statistics from U.S. Drought Monitor.
State boundaries from U.S. Census Bureau cartographic boundary file.

Methods:

Downloaded state-level drought statistics from the U.S. Drought Monitor as a CSV (percent of area, categorical values).
Downloaded state boundaries from the U.S. Census Bureau
Joined the drought table to the state boundaries in Mapshaper.
Built the web map in Leaflet.

Design Choices:

Muted basemap: Esri Light Gray Canvas kepps the background neutral so the drought colors stand out.
Sequential color ramp: YlOrRd runs from light yellow (little moderate drought) to dark red (widespread moderate drought).
Consisent styling: the panel glow uses the darkest color of the ramp to tie the interface to the map.

Built with:

Leaflet 1.7.0, the mapping library.
leaflet-ajax 2.1.0, which loads the GeoJson file.
chroma.js 1.3.4, which generates the color ramp.
jQuery 3.1.0, which builds the legend
Esri World Light Gray Canvas basemap.

Author:

Chris Bennett, Appalachian State University.


