# UAV Band-to-Band Registration for 4x-band RGBN Imagery

Name: drone_fp.py
>The purpose of this module is to calculate imagery footprints or field of view (FOV).  This is 
>accomplished by using exiftags from drone images to generate polygons for each image.  The output is 
>a GeoJSON file with:
>* Drone Flightpath (LineString)
>* Mission Area (Polygon)
>* Individual Image Footprints (Polygons)
----------------------------------------------------------------------------------------------------------------

Author: Dean Hand <br>
Date Created: 09/07/2019<br>

----------------------------------------------------------------------------------------------------------------
## Input<br/>
`-i` - The Default root folder for the mission you wish to processes.  Required

## Output<br/>
`-o` - The output directory for the GeoJSON file. Not Required

## Sample Dataset
A sample dataset can be found [here](https://drive.google.com/drive/u/1/folders/1Hwrhi-eK_-i8R2NQ3churBls-i4aAXg9)

## Sample JSON Output 
A sample of the json output can be found [here](https://drive.google.com/open?id=1RhSlY9KL2NYpnnVyNqI5c6cLzC0YWMTj)