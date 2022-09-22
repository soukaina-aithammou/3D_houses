# 3D_houses
Mission:
model a house in 3D with only a home address.

Requirements:
Python
requests
json
os
rasterio
plotly
pandas

Steps:
Collecting Data:
-DTM files for Flanders: http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dtm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DTM,%20raster,%201m
-DSM files for Flanders: https://www.geopunt.be/download?container=dhm-vlaanderen-ii-dsm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DSM,%20raster,%201m
-Data of each address in Flanders: https://api.basisregisters.vlaanderen.be

-Providing the address
-Match the address with the correct API.
-Get the coordinates.
-Check this coordinates in which file DSM and DTM.
-Clip the target zone from the DSM.tif.
-Clip the target zone from the DTM.tif.
-Subtract the Clipped DTM from the Clipped DSM to compute The Canopy Height Model CHM.
-Plot the CHM.

