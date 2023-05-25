# A3
Shapely is a python library that can be used for geospatial data analysis by creating shaped geometric objects (e.g. points, polygons, polygons) and manipulating them, such as buffering, calculating areas or intersections, etc.

So I want to define a rectangle object and calculate its area by using Shapely.

I created a rectangle object using the Polygon class which accepts a list of coordinates as an argument.

Next, I defined the coordinates of the four vertices of the rectangle and then used the zip function to pack the x and y coordinates together in order to create the Polygon object. 

Finally, I calculated the area of the rectangle using the area property and printed the result.
