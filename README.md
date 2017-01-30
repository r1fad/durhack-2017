# Durhack 2017
Visualizing car parks, cemeteries and  internet access points

## What it does
The website we have built visualizes places in Durham County where you can find access to the internet, car parks, public libraries and cemeteries.

## How we built it
We obtained CSV files from Data Mill North, converted the Easting and Northing coordinates to Latitiude and Longitude and then used Google Maps API to plot markers on the map. Quite simple actually :)

## Challenges we ran into
The datasets did not provide Latitudes and Longitudes and so we had to convert the Easting and Northing coordinates into Latitude and Longitude. We had to make sure that the conversion presereved the format of the dataset.


