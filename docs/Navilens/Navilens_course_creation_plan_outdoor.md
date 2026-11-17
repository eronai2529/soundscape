# Outdoor RPI Navilens Course Plan

## Summary
We plan to place Navilens codes outside 5 buildings around the RPI Campus, as well as 1 bus stop. These buildings include Russell Sage Dining Hall, Low Center for Industrial Engineering, the Ricketts Building, Russell Sage Laboratory, and Amos Eaton Hall. These buildings were chosen it order to allow for a buffer distance between them so that Soundscape will individually call up Navilens each time a Navilens code is near.

## Exact Code Locations

Russell Sage Hall

Cooridinates: 42.72989823, -73.67823186

![Russell Sage Hall Main Entrance](./CodeLocations/IMG_0159.heic)

![Russell Sage Hall Side Entrance](./CodeLocations/IMG_0161.heic)


Low Center for Industrial Engineering

Cooridinates: 42.72967093, -73.67885401

![Low Center for Industrial Engineering](./CodeLocations/IMG_0163.heic)


Ricketts Building

Cooridinates: 42.73078602, -73.67978698

![Ricketts Building](./CodeLocations/IMG_0165.heic)


Russell Sage Laboratory

Cooridinates: 42.73075298, -73.6816943

![Russell Sage Laboratory](./CodeLocations/IMG_0166.heic)


Amos Eaton Hall

Cooridinates: 42.73015875, -73.6822676

![Russell Sage Laboratory](./CodeLocations/IMG_0166.heic)

## Details

The codes will be hung on laminated paper (shiny surface should not have a great impact on detection as cleared by Dr. Turner) on campus in places general postering is allowed. They will be hung on the week 11/15/26-11/28/26. The codes required for this course will be newly generated using the Soundscape account of the Navilens Authoring tool. The location of the Navilens codes will then be added by a developer with server access to the csv files on the server that handle the locations of Navilens codes.

## Creating Navilens Codes

There are 3 ways to create Navilens Codes for use:

Creating Accessible QR Codes:

These codes are functionally regular QR codes that can read out text and then link to websites. They do not look like typical Navilens Codes, but are customizable for those without a Navilens Authoring tool Account. 

Requesting Educational Codes:

These codes are typical Navilens Codes, however they are hard coded to have specific values. These values are written in Navilens_free_codes_summary.md. This makes them inconvenient to use as you cannot encode specific values is. The plan for the RPI outdoor Navilens Course is to use the Educational Codes that coorespond to the map numbers of buildings on the official RPI map, (specifically, 6,10,13,14,26). These will later be updated with Navilens Codes that coorespond to building names, but the numbers will allow us to dry run the course.

Navilens Authoring Tool:

The Navilens Authoring Tool allows a user to create new Navilens Codes themselves. These codes must be stored on Navilens's internal servers so they require a commercial account. Soundscape has one such account to license codes and this will allow the RPI Outdoor Course to eventually have Navilens Codes that coorespond to the building names.