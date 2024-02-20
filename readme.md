# Polar Bromine Model Intercomparison

## Description 
Our plan is to compare and evaluate 3D atmospheric models which include polar halogen sources and reproduce surface ozone depletion. Models will be evaluated against in situ and satellite observations in the Arctic from Spring 2012 and Spring 2020.

This intercomparison is a part of CATCH (the Cryosphere and Atmospheric Chemistry, https://www.catchscience.org/)

## Updates on Timing and Participation - as of 28 Nov 2023
We plan to collect model runs completed by the end of the month of January 2024 for analysis.  Particpation is open for any groups who would like to join, but we cannot ensure your model outputs will be included if we do not have them available to the group by 1 Feb 2024.

| Models | 2012 time series | 2012 NetCDF files | 2020 time series | 2020 NetCDF files |
|--------|------------------|-------------------|------------------|-------------------|
| WRF-Chem |  Not received  |    Not received   |   Not received   |    Not received   |
| EMAC |  Not received  |    Not received   |   Partially received  |    Not received   |
| CAM-CHEM |  Not received  |    Not received   |   Not received   |    Not received   |
| Geos-Chem |  Not received  |    Not received   |   Not received   |    Not received   |
| GEM-MACH-Arctic |  Received  |    Not received   |   Received   |    Not received   |
| p-TOMCAT |  Not received  |    Not received   |   Not received   |    Not received   |

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
- William Simpson (University of Alaska Fairbanks)
  - Data provider, Ozone at O-Buoys and BrO observed by MAX-DOAS in Utqiaġvik

## Next meeting
- Please join our mailing list to get all the meeting info!

## Past meetings

### 17 Jan 2024

#### 1. Summary of where modeling groups are with their runs
Most modeling groups are proceeding nicely with plans to finish first runs by mid Feb.  We don’t plan to collect large netcdf files from all runs.  
- Instead we plan to ask you to extract the values suggested at the O-Buoy, surface stations, and MOSAiC ship track (3-hourly data if possible) and provide text files with your output to us at IGE for comparing all the models.
- We feel this is a first step before we start plotting maps of all the model output together.  Please keep your original output files to provide netcdf files for comparison later.
- We have corrected some station locations on the GitHub following our discussion.  If you find any more/uncorrected errors, please email Remy Lapere and Louis Marelle to have them corrected on the GitHub.
- Update 25 Jan 2024 - after meeting - we updated the emissions rates and other rates recommended to save as accummulated over 3 hours in each 3 hourly output file.

#### 2. Model versions
- We hope models run in configurations that are published in the literature, with model versions that can be referenced by summer 2024 (no major model updates just for this inter comparison).

#### 3. Questions regarding output requirements
- We have updated the GitHub output instructions here: https://github.com/jenniethomas/arctic-bromine-model-intercomp/blob/main/outputVariablesObs.md. Main changes: Updates to recommended output variables, variable names, updates to recommended output frequency, instructions for extractions at surface stations, O-Buoys, MOSAiC ship track.  An example text file format we hope to get from you with the extraction for the surface observations is provided.  Please do not provide averages, but run output each 3 hours.
- Please keep your full run output on your own servers - we will work on a strategy for comparing maps, vertical profiles, and other comparisons on our next call.
- There was a discussion on the need for total aerosol output from the models, so we suggest to extract PM2.5, PM10, and total aerosol mass to look at the role of Arctic haze in sustaining heterogenous Br recycling / ozone depletion.  Models that can save total Br2 formation rates due to heterogenous reactions on aerosols (including sulphate aerosols) please do so and we’ll try to find a way to compare this.
- We need to provide a specific format for the text files to be provided, we will do this shortly.
- Comparing with BrO partial columns can also be explored in the future (using data from Bill or Alfonso)

#### 4. Summary of publicly available data that can be used for comparison / evaluation
- There was a discussion about comparing with vertical profiles during MOSAiC, this issue is tabled until the measurements are available publicly and we have completed a comparison with publicly available ground/o-buoy/ship based observations.

#### 5. Comparison with Satellite remote sensing
- There was a typo on our GitHub regarding the requested model output, this is corrected [here](https://github.com/jenniethomas/arctic-bromine-model-intercomp/blob/main/outputVariablesObs.md).  Andreas and Bianca want output on model levels.  Modeling groups should send a small test file of your output to Andreas and Bianca as soon as you are ready to ensure they can understand how to compare your output with their retrievals.

#### 6. Establishment of a code of conduct for our group / discussion and agreement
- We have drafted a code of conduct following our last meeting, [found here](https://github.com/jenniethomas/arctic-bromine-model-intercomp/blob/main/Code_of_conduct.md).
Please provide any feedback by email to Louis and Jennie.

#### 7. Join our Slack for interactive discussions 
- please email us to get the link to join our slack.

We plan to have our next meeting in early March - stay tuned for details.

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
