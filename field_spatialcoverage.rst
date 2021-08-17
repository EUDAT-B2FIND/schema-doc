.. _d:spatialcoverage:

Spatial Coverage (O)
--------------------
Spatial region or named place where the data was gathered or which the data is about (occurrence: 0-n). If geocoordinates are provided, the region will be displayed on the map.
EUDAT Core offers the following possibilities to display geographical information:
geoLocationPlace
geoLocationPoint
geoLocationBox
geoLocationPolygon

**Allowed values, examples, other constraints**
Recommended, in accordance with DataCite: Use WGS 84 (World Geodetic System) coordinates. Use only decimal numbers for coordinates. Longitudes are -180 to 180 (0 is Greenwich, negative numbers are west, positive numbers are east), Latitudes are -90 to 90 (0 is the equator; negative numbers are south, positive numbers north).


Example
~~~~~~~
.. code-block:: xml
   :linenos:

   <spatialCoverages>
      <spatialCoverage>
          <geoLocationPlace>Atlantic Ocean</geoLocationPlace>
          <geoLocationPoint>
              <pointLongitude>-67.302</pointLongitude>
              <pointLatitude>31.233</pointLatitude>
          </geoLocationPoint>
          <geoLocationBox>
              <westBoundLongitude>-71.032</westBoundLongitude>
              <eastBoundLongitude>-68.211</eastBoundLongitude>
              <southBoundLatitude>41.090</southBoundLatitude>
              <northBoundLatitude>42.893</northBoundLatitude>
          </geoLocationBox>
      </spatialCoverage>
      <spatialCoverage>
          <geoLocationPolygon>
              <polygonPoint>
                  <pointLatitude>41.991</pointLatitude>
                  <pointLongitude>-71.032</pointLongitude>
              </polygonPoint>
              <polygonPoint>
                  <pointLatitude>42.893</pointLatitude>
                  <pointLongitude>-69.622</pointLongitude>
              </polygonPoint>
              <polygonPoint>
                  <pointLatitude>41.991</pointLatitude>
                  <pointLongitude>-68.211</pointLongitude>
              </polygonPoint>
              <polygonPoint>
                  <pointLatitude>41.090</pointLatitude>
                  <pointLongitude>-69.622</pointLongitude>
              </polygonPoint>
              <polygonPoint>
                  <pointLatitude>41.991</pointLatitude>
                  <pointLongitude>-71.032</pointLongitude>
              </polygonPoint>
          </geoLocationPolygon>
      </spatialCoverage>
  </spatialCoverages>

