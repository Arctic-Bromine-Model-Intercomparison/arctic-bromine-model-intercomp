# Polar Bromine Model Intercomparison

## Description 
Our plan is to compare and evaluate 3D atmospheric models which include polar halogen sources and reproduce surface ozone depletion. Models will be evaluated against in situ and satellite observations in the Arctic from Spring 2012 and Spring 2020.

This intercomparison is part of CATCH (the Cryosphere and Atmospheric Chemistry, https://www.catchscience.org/)

## Updates on Timing and Particpation - as of 28 Nov 2023
We plan to collect model runs completed by the end of the month of January 2024 for analysis.  Particpation is open for any groups who would like to join, but we cannot ensure your model outputs will be included if we do not have them available to the group by 1 Feb 2024.

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
- Jennie Thomas, Louis Marelle (CNRS-IGE/LATMOS)
  - Model: WRF-Chem
  - Model version: https://doi.org/10.1525/elementa.2022.00129
- Björn-Martin Sinnhuber, Stefanie Falk, Luca Reissig (KIT-IMK-ASF)
  - Model: EMAC
  - Model version: https://doi.org/10.5194/gmd-11-1115-2018
- Rafael Fernandez, Orlando Tomazzeli, Alfonso Saiz-Lopez (ICB-CONICET)
  - Model: CAM-CHEM
  - Model version: https://doi.org/10.1029/2019MS001655
- Chris Holmes (FSU)
  - Model: Geos-Chem
  - Model version: https://doi.org/10.5194/acp-22-14467-2022
- Kenjiro Toyota, Wanmin Gong (CCCma/ECCC)
  - Model: GEM-MACH-Arctic
  - Model version: https://doi.org/10.5194/acp-18-16653-2018, https://doi.org/10.5194/acp-22-5775-2022
- Xin Yang (BAS)
  - Model: p-TOMCAT
  - Version: https://acp.copernicus.org/articles/20/15937/2020/
- Andreas Richter (IUP-Bremen)
  - Satellite comparison of models with retrievals of BrO

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
