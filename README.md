# World Crop Visualization

This is a zoomable sunburst displaying world crop production from 1961 to 2017. The data is from FAOSTAT and converted from a csv file into a nested json object. I used D3 to render the data as an interactive graph.

Check it out [here](https://gregory-rempe.com/worldCropVisualization/).

The drop down menu is used to select which year you would like to display. Each year has around 9,500 data points.
When you click on a wedge, the sunburst will re-render with the selected wedge as the new center and its children distributed around the sunburst. Clicking on the center will zoom out.

A tooltip will appear on mouse over displaying the name of the wedge, its production in tonnes and the percent of the whole it makes up. 

![World Crop Production](https://github.com/gmrempe/worldCropVisualization/blob/master/Screen%20Shot%202019-08-15%20at%2011.34.09%20AM%20copy%202.png)

