# World Crop Visualization

This is a zoomable sunburst displaying world crop production from 1961 to 2017. The data is from FAOSTAT and converted from a csv file into a nested json object. I used D3 to render the data as an interactive graph.

Check it out [here](https://gregory-rempe.com/worldCropVisualization/).

![World Crop Production](https://github.com/gmrempe/worldCropVisualization/blob/master/Screen%20Shot%202019-09-27%20at%2011.23.27%20AM.png)

The drop down menu is used to select which year you would like to display. Each year has around 9,500 data points.
When you click on a wedge, the sunburst will re-render with the selected wedge as the new center and its children distributed around the sunburst. Clicking on the center will zoom out. The image below is zoomed in on Maize.

![Zoom in on a crop](https://github.com/gmrempe/worldCropVisualization/blob/master/Screen%20Shot%202019-09-27%20at%2011.24.03%20AM.png)

A tooltip will appear on mouseover displaying the name of the wedge, its production in tonnes and the percent of the parent's production the wedge represents. For example, below the tooltip is showing that Brazil produces 41.19% of the world Sugar Cane crop, the parent element. If the mouse was hovering over Sugar Cane the percentage would represent the amount of Sugar Cane relative to all crops produced in a year.

![Mouseover on Brazil](https://github.com/gmrempe/worldCropVisualization/blob/master/Screen%20Shot%202019-09-27%20at%2011.34.08%20AM.png)
