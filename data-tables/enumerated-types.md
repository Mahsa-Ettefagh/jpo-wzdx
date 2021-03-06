# Enumerated Types
This section includes a table of enumerated data elements. An enumerated type is a special data type that enables for a variable to be a set of predefined constants otherwise known as factor data. The variable must be equal to one of the values that have been predefine for it. 

#### Table 7. Enumerated Types
Data Element | Used by | Allowed Values | Notes | Source
------------ | ------- | -------------- | ----- | ------
**wz-Status** | WorkZoneActivity | See Enumerated Type<br>Definitions (Table 8) 
**roadDirection** | BeginLocation | <ul><li>northbound</li><li>eastbound</li><li>southbound</li><li>westbound</li></ul> |  | Adapted from<br>TMDD link-<br>alignment
**roadRestriction** | RoadRestrictions | <ul><li>no-trucks</li><li>travel-peak-hours-only</li><li>hov-3</li><li>hov-2</li><li>no-parking</li><li>bike-lane</li><li>ramp</li><li>towing-prohibited</li><li>permitted-oversize-loads-<br>prohibited (this applies to<br>annual oversize load<br>permits</li><li>reduced-width</li><li>reduced-height</li><li>reduced-length</li><li>reduced-weight</li><ul><li>axle-load-limit</li><li>gross-weight-limit</li></ul></ul> | Included one<br>or more<br>flags as needed | See<br>definitions<br>below
**laneType** | openLanes,<br>closedLanes | <ul><li>all</li><li>left-lane</li><li>right-lane</li><li>left-2-lanes</li><li>left-3-lanes</li>right-2-lanes</li><li>right-3-lanes</li><li>center</li><li>middle-lane</li><li>right-turning-lane</li><li>left-turning-lane</li><li>right-exit-lane</li><li>left-exit-lane</li><li>right-merging-lane</li><li>left-merging-lane</li><li>right-exit-ramp</li><li>right-second-exit-ramp</li><li>right-entrance-ramp</li><li>right-second-entrance-ramp</li><li>left-exit-ramp</li><li>left-second-exit-ramp</li><li>left-entrance-ramp</li><li>left-second-entrance-ramp</li><li>sidewalk</li><li>bike-lane</li><li>none</li><li>unknown</li><li>alternate-flow-lane</li><li>shift-left</li><li>shift-right</li></ul> |  | Adapted from<br>TMDD<br>LaneRoadway
**closedShoulders** | WorkZoneActivity | <ul><li>outside</li><li>inside</li><li>both</li><li>none</li><li>unknown</li></ul> |  | Adapted from<br>TMDD<br>LaneRoadway
