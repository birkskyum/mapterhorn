Rows south of 85°S that mapterhorn/mapterhorn#336 adds, for a MapLibre demo that lays them over the southernmost Mapterhorn tiles up to zoom 6.

`z{z}.png` holds, for each tile x of the bottom tile row at zoom z, the rows of that 512 px tile that reach south of 85°S, stacked top to bottom from x = 0, terrarium encoded in whole meters. They come from the Copernicus GLO-30 rows S85_00 and S86_00, warped to Web Mercator at zoom 6 with GDAL and averaged down for the lower zooms.

The Copernicus DEM is © DLR e.V. 2010-2014 and © Airbus Defence and Space GmbH 2014-2018 provided under COPERNICUS by the European Union and ESA, all rights reserved.
