# Polar Bromine Model Intercomparison

## Description 
Our plan is to compare and evaluate 3D atmospheric models which include polar halogen sources and reproduce surface ozone depletion. Models will be evaluated against in situ and satellite observations in the Arctic from Spring 2012 and Spring 2020.

## How to Join
Email jennie.thomas@univ-grenoble-alpes.fr with your github login to be added to this repository (https://github.com/jenniethomas/arctic-bromine-model-intercomp/) and to the project's google group (https://groups.google.com/g/arcbromintercomp).

## Simulation instructions for Spring 2012 and Spring 2020 case studies
Spring 2012 case study:
- Simulation dates: 2012/03/01 00 UTC to 2012/06/01 00 UTC (+ appropriate model spinup so that March 1st data is usable)
- Simulation domain (for regional models): needs to include the whole Arctic above the Arctic Circle + Hudson Bay

Spring 2020 case study:
- Simulation dates 2020/03/01 00 UTC to 2020/06/01 00 UTC (+ appropriate model spinup so that March 1st data is usable)
- Simulation domain (for regional models): needs to include the whole Arctic above the Arctic Circle + Hudson Bay

There are no other requirements for emissions, driving meteorological data or other detailed model setup options.

## Observations used for the comparisons, required model output
See detailed  instructions in instructions.md (https://github.com/jenniethomas/arctic-bromine-model-intercomp/blob/main/outputVariablesObs.md)

## Confirmed participating groups, models, & main contacts
- To be listed.

## Next meeting
- Please join our mailing list to get all the meeting info!

## Past meetings
### 8 Dec 2022 at 16:30 to 17:30, CET
- Decided on run dates 
- Decided to focus on the Arctic cases, Antarctic case studies could be run as a second step by the modeling groups who are interested
- Discussed output variables:
  - Decided to rename the 2nd and 3rd categories of output, into 'highly recommended', then 'nice to have', this will be updated in the next few weeks and circulated for comment
  - Decided to add OH, HO2, NO, NO2, PM2.5 and PM10
  - Decided global model output only needs to be saved above 50N to include the Arctic and Hudson Bay 
  - Decided regional model domains need to cover the Arctic Circle + Hudson Bay (not necessarily the full > 50N area outside of Hudson Bay).
  - Agreed 3-hourly 3D output of BrO,T,P is needed for comparing to satellite BrO.
  - Other 3-hourly output is required to interpolate at location of observations for evaluating the models. The full 3-hourly 2D fields or 3D fields are not required if models can perform this interpolation at runtime - but the 3-hourly 2D fields are still highly recommended.
  - PBL height can be calculated in several ways - models will provide their standard PBLH output and an explanation of how it is calculated.
- Encouraged all modeling groups to fill out our participation survey - https://doodle.com/meeting/participate/id/e98Bkn8d
- Next meeting will focus on getting obervational datasets identified and lat/lon/alt/times for interpolation of model data.


### 6 Sept 2022
- presentation: https://docs.google.com/presentation/d/1l1xKaok0uo2QOVU-icYYkir6onIUyFH1ILIkRZ3w1h4/edit?usp=sharing 
- attendees: https://etherpad.wikimedia.org/p/Polar-bromine-intercomp-6Sept2022
