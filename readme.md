README: WWF Living Planet Pods Data
===================================

This repo contains static files of data for use in the WWF Pods project. Subfolders should give you some idea of what the contained data consists of, and there is a seperate readme in many of the folders with background information

Key Data
========

We have created a system which ingests data sources (eg, CSV files published from google spreadsheets) and indexes them, making them available through a JSON API.

Interesting sources are:

## Rhino Reports

http://wwf-brain.appspot.com/api/content.get?status=approved&sourceKey=agtzfnd3Zi1icmFpbnIPCxIHU291cmNlcxiOkwwM

Updates from a Rhino warden in the field. NB DO NOT attempt to geolocate rhino: this places them at severe risk from poaching, and also risks sending our rhino staff to prison, as this is a punishable offense in Kenya

## Rhino infomation

The rhinos that might be mentioned in the reports - DOB, weights...

## Hyena Data

Tracking data from hyena collars

Available as a spreadsheet in the repo (see readme, and also geolocation data), and also via


## Mara River Flow Data

Measurements from a sonde in the Mara River. Available as a spreadsheet in the repo (see readme, and also geolocation data)

## Polar Ice Data

Available both from within the brain, and as a completely seperate API thanks to @infovore

http://polarice.herokuapp.com

## All Sources

All CSV sources in the can be accessed at this endpoint:

http://wwf-admin.appspot.com/collection/agtzfnd3Zi1icmFpbnITCxILQ29sbGVjdGlvbnMY6qMmDA

ADDITIONAL DATA SOURCES
=======================

Lists of other possible data sources are in a google spreadsheet here: 

https://docs.google.com/a/storythings.com/spreadsheet/ccc?key=0AuoTOgL4XBqadDh2cTRBWXdvRHpQaHBLdVJCQXNEdmc#gid=2 

(arranged in sheets)

These are very varied, and classified roughly as geographic, species, etc, and refer to which 'pod' (think: topic) they relate to. Some are more general - eg global weather data, species taxonomies etc. All are annotated reasonably well: I've done my best to provide developer-friendly notes!

There are also content sources listed: these might be best consumed via the Mara Pods collection:

http://wwf-brain.appspot.com/api/content.get?status=approved&tags=pod:mara

Note status=approved - the Pods system allows some editorial control to prevent leaking sensitive data.

##Some interesting ideas:

How does river height change affect movement of hyenas? They tend to follow wildebeeste herds, which migrate according to rains...

How could we combine high resolution satellite data with on-the-ground reports? What could we demonstrate to people?

There's some Kenyan govt data in there about flush toilets per dwelling: what happens if this is added to the Mara River data?
