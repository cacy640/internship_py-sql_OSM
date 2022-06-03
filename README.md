# internship_py-sql_OSM
Internship at UAL: retrieve data from database using SQL embedded in python, cleaning height &amp; roof data for vairious cities, and try to perform clustering.


cleaning_dec03.ipynb contains the code (Python+SQL) of the process of retrieving OSM data of a few cities from the internal database, and the code for cleaning ```height``` ```building:levels``` and ```roof:levels```. Cleaning ```height``` is to remove non-numeric values and to standardize the metric units into "m". Cleaning ```building:levels``` and ```roof:levels``` is to standardize the form of values.

clustering_dec_20.ipynb contains the code (Python) that performs the possible clustering outcome of these OSM tag values. 

planet.ipynb is the code that I put on the server to retreive the OSM data of the entrie planet from the database
