## Project Desctiption

To create and do accuracy analysis on an SfM-MVS product

## Project Location

Swindale River, in Swindale Valley (Grid Ref NY 512 129), in Cumbria County. 

At that time, at the river were  extensive ground work was under way for it's ‘de-linearization’.   The
site is located approximately 20 km South-West from the nearby city of  Penrithin  Cumbria. The location is managed 
 by the RSPB. 

## Time and date of the survey:
29th of August 2016 between 11:00 to 18:00.


## Files and Folders Description:

##### 1_Photos:
The Folder contain the raw in JPG formatimages WITHOUT any geolocation information. The UAV was flawn at 29th of August 2016 at Swindale Valley

- The photos contain photographic parameteres.



|Camera specs| |
|---|---|
|Camera Model|Canon IXUS 240 HS
|Dimensions| 92.2 x 55.9 x 19.5mm|
|Sensor Focal Length| 4.4 mm|
|Sensor Width| 6.259 mm|
|Sensor Height| 4.794 mm|
|Image X| Size 4000|
|Image Y| Size 3000|
|Footprint @ 70m| 108 m x 81 m|


##### 2_ImageGeolocations

A CSV file  file containing the GEOLOCATION information of each IMAGE as reported by the UAV's GPS. 
(Note: Geolocation in this context means the location of the GPS sensor of the UAV)

Latitude,Longitude (EPSG:4326) and GPS Altitude (m)

##### 3_TargetCoordinates
The Folder contains two files.
- TargetCoordinates_wAccuracy.csv
- ImageTargets.csv


###### TargetCoordinates_wAccuracy.csv:
This CSV contains the coordinates of all GCPs and their labels. The Coordinate System is the UK National Grid (EPSG: 27700). 

The coordinates were captured using an RTK-GPS tied to a near by Base Station which we setup for the project.   (BaseName name:ref)
CSV file with the Coordinates of each GCP, containing the following:
||
|---|
|Label|
|Easting|
|Northing| 
|Height|
|Accuracy horizontal|
|Accuracy Vertical|
The coordinate system is OSGB32, epsg code: 27700

###### ImageTargets.csv
This CSV contains contains the coordinates for each target found in each image. 

> The coordinatates are in image coordinates: 
>
> x: Left to Right 
> y: Top to Bottom

##### 4_FlightPaths
Folder contais 3 KML files that can been seen withing Google Earth or a similar program. The KMLs depict the the flight paths of the UAV. Each node represents a position where an image was taken.

