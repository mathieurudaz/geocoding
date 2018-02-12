gdal_translate viewshed_clipped.tif viewshed_clipped.png -outsize 2400 2232 -of PNG -ot Byte -scale 0 47 0 255 -a_srs EPSG:3857

Use SAGA dissolve instead of the standard one which doesn't work.