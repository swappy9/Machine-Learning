# Crime-pattern-detection
Crime pattern detection - multi classification problem

The MPD has published a record of the crimes over a period of time. Based on this
dataset, they are willing to predict the type of crime.
This way, they would know ahead of time what kind of incident they should be expecting
and what backup resources they may need.
You are asked to help the MPD develop such predictive models. The input features of
the given data  are:

{ incident datetime: This is a variable indicating the time and the date that an
incident happened.

{ incident cord x: This is the x-coordinate of the location that the incident happened.

{ incident cord y: This is the y-coordinate of the location that the incident happened.

{ num victims: This is a variable indicating the number of victims in the incident.

{ location type: A variable that indicates the type of location the incident happened,
location types are identied by numbers and may correspond to dierent points such
as residential, roads, public gardens, etc. If for a crime the location type has not been
reported, the location type for that incident takes a value of zero.


The response variable is:
{ Crime Type: This is a variable that indicates the type of the crime that took place.
This is a categorical variable and takes one of the following values:
{ \AGG ASSAULT"
{ \AUTO THEFT"
{ \BURGLARY-NONRES"
{ \BURGLARY-RESIDENCE"
{ \HOMICIDE"
{ \LARCENY-FROM VEHICLE"
{ \LARCENY-NON VEHICLE"
{ \RAPE"
{ \ROBBERY-COMMERCIAL"
{ \ROBBERY-PEDESTRIAN"
{ \ROBBERY-RESIDENCE"
