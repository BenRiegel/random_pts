# Random Point Generator

This project demostrates how to create a series of random points within a specific bounding geometry. In a jupyter notebook, I walk through the steps of accessing the bounding polygon from a shapefile, creating random points within the bounding rectangle of the polygon, testing whether the points fall within the polygon itself, and finally saving the points to a new file.

The "data" folder for the project contains the main input dataset "mdi.shp". This file contains the geometry of Mount Desert Island in Maine. The python code is contained in the notebook "analysis.ipynb". The file "random_points.shp" is the output dataset. The "environment.yml" file contains a list of all the python packages that the code requires to work.
