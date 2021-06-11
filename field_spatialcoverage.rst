.. _d:spatialcoverage:

Spatial Coverage (O)
--------------------
Spatial region or named place where the data was gathered or which the data is about (occurrence: 0-n). If geocoordinates are provided, the region will be displayed on the map.
B2FIND offers the following possibilities to display geographical information:
geoLocationPlace
geoLocationPoint
geoLocationBox
geoLocationPolygon

**Allowed values, examples, other constraints**
Recommended, in accordance with DataCite: Use WGS 84 (World Geodetic System) coordinates. Use only decimal numbers for coordinates. Longitudes are -180 to 180(0 is Greenwich, negative numbers are west, positive numbers are east), Latitudes are -90 to 90 (0 is the equator; negative numbers are south, positive numbers north).


Example
~~~~~~~
.. code-block:: xml
   :linenos:

   <keywords>
	<keyword>Chemistry</subject>
	<keyword>Catalysis</subject>
	<keyword>Confinement</subject>
	<keyword>Metathesis</subject>
   </keywords>
