#NIR

### Introduction

This repository provides information collected from several Translink -
Northern Ireland Rail sources and provides information about each
location.

There are two types of location in this file:

###### Type `R`
These locations are generally stations and halts that accept passengers.
Each of these locations should have a real_time id and a timetable id,
as well as a location.

Locations such as Dundalk, Drogheda and Dublin Connolly are also
included in this group.

###### Type `other`

These locations are generally locations that trains on the network pass
through without collecting or putting down passengers, such as junctions and sidings, or Irish Rail/Iarnród Éireann stations the Enterprise passes without stopping.


### Locations

`_ids`
This is a collection of ids that relate to the location across several
sources

`easting/northing`
These are coordinates for the location according to the Ordnance Survey
National Grid reference system.

`real_time_crs`
The location's CRS code as provided by the [Translink Real Time Rail Stations Arrivals and
Departures API](https://www.opendatani.gov.uk/dataset/real-time-rail-stations-arrivals-and-departures)

`real_time_id`
A code used to identify the location for the [Translink Real Time Rail Stations Arrivals and 37 Departures API](https://www.opendatani.gov.uk/dataset/real-time-rail-stations-arrivals-and-departures).

`timetable_id`
An id used to reference the location in the [Translink Northern Ireland
Rail Timetable](https://www.opendatani.gov.uk/dataset/nir20160126v2).



