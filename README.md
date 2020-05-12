# tile-services

This repo serves as practice using tile generation and customization services as part of GEOG 458 at the UW.

For this map I decided to generate tiles for the general LA area in California. 

The tiles were generated from Mapbox through customizing a dark theme. I made a few tweaks and customizations while playing with the basemap editor. One tweak is the fact that the roads will dissapear as you zoom further in.

I rendered from zoom 0 to 12 in QGIS using QMetaTiles. This resulted in assets around 150mb in size, which is quite large for a GitHub repo.

The map was defaulted to a zoom of 9 as that makes my generated tiles take up a large portion of the page.
