# Required model output variables
The absolute minimal results to provide in the intercomparison are the following:
- 3-hourly 2D/3D variables in the table below, interpolated along relevant observation stations and campaigns
- 3-hourly 3D BrO,T,P data in the table below, processed appropriately for comparison to satellite BrO observations
- Daily 2D variables from the table below.

We strongly recommend that all the full 2D/3D fields in the table below are saved, so that interpolations and analysis can be redone in case of errors.

| Variable      | Unit | Dimensions | Frequency |
| ----------- | ----------- | ---------------- | ------------|
| Surface $O_3$ mixing ratio | ppbv | 2 | 3-Hourly |
| Surface BrO mixing ratio | ppbv | 2 | 3-Hourly |
| Surface dry sea salt aerosol mass concentration < 10 ${\mu}m$ diameter | $\mu g/m^{3} (ambient)$ | 2 | 3-Hourly |
| 2-meter air temperature | K | 2 | 3-Hourly |
| Surface pressure | Pa | 2 | 3-Hourly |
| 10-m wind speed | m/s | 2 | 3-Hourly |
| Boundary layer height | m | 2 | 3-Hourly |
| BrO mixing ratio for satellite comparison | $ppbv$ | 3 | 3-Hourly |
| Air temperature for satellite comparison | K | 3 | 3-Hourly |
| Air pressure for satellite comparison | Pa | 3 | 3-Hourly |
| Sea ice concentration | \% | 2 | Daily |
| $Br_2$ emissions| $moles/m^{2}$ | 2 | Daily |
| Sea salt aerosol emissions| $mg/m^{2}$ | 2 | Daily |
| Altitude of lowermost model level | m AGL + m ASL| - | - |

In addition, the following information should be saved:
- Model grid dimensions: time, latitude, longitude, layers, levels
- Model information/attributes: provider, model, version, creation_date

# Highly recommended model output
If some of these variables cannot be saved by your model, saving some is better than none!
| Variable      | Unit | Dimensions | Frequency |
| ----------- | ----------- | ---------------- | ------------|
| $O_3$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| Sea salt aerosol mass concentration < 10 ${\mu}m$ | $\mu g/m^{3}$ | 3 | 3-Hourly |
| Sea salt aerosol number concentration < 10 ${\mu}m$ | \# $/m^{3}$ | 3 | 3-Hourly |
| $PM_{2.5}$ mass  | ${\mu}g/m^{3}$ | 3 | 3-Hourly |
| $PM_{10}$  mass | ${\mu}g/m^{3}$ | 3 | 3-Hourly |
| Total aerosol mass | ${\mu}g/m^{3}$ | 3 | 3-Hourly |
| Surface Wind speed | $m/s$ | 2 | 3-Hourly |
| Surface Wind direction | $^\circ$ | 2 | 3-Hourly |
| Surface Relative or specific humidity | \% or $kg/kg$ | 2 | 3-Hourly |
| Surface $Br_2$ mixing ratio | $ppbv$ | 2 | 3-Hourly |
| Surface OH mixing ratio | $ppbv$ | 2 | 3-Hourly |
| Surface $HO_2$ mixing ratio | $ppbv$ | 2 | 3-Hourly |
| Boundary layer height | $m$ | 2 | 3-Hourly |
| Sea ice concentration | \% | 2 | Daily |
| $Br_2$ emissions from surface snow| $moles/m^{2}$ | 2 | Daily |
| $Br_2$ emissions from blowing snow| $moles/m^{2}$ | 2 | Daily |
| $Br_2$ emissions from sea spray| $moles/m^{2}$ | 2 | Daily |
| Sea salt aerosol emissions from blowing snow| $mg/m^{2}$ | 2 | Daily |
| Sea salt aerosol emissions from sea spray | $mg/m^{2}$ | 2 | Daily |

# Nice-to-have model output
If some of these variables cannot be saved by your model, saving some is better than none!
| Variable      | Unit | Dimensions | Frequency |
| ----------- | ----------- | ---------------- | ------------|
| $Br_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| OH mixing ratio | $ppbv$ | 3 | 3-Hourly |
| $HO_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| HOBr mixing ratio | $ppbv$ | 3 | 3-Hourly |
| HBr mixing ratio | $ppbv$ | 3 | 3-Hourly |
| ClO mixing ratio | $ppbv$ | 3 | 3-Hourly |
| $Cl_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| HOCl concentration | $ppbv$ | 3 | 3-Hourly |
| HCl mixing ratio | $ppbv$ | 3 | 3-Hourly |
| IO mixing ratio | $ppbv$ | 3 | 3-Hourly |
| $I_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| NO mixing ratio | $ppbv$ | 3 | 3-Hourly |
| NO2 mixing ratio | $ppbv$ | 3 | 3-Hourly |
| Wind speed | $m/s$ | 3 | 3-Hourly |
| Wind direction | $^\circ$ | 3 | 3-Hourly |
| Relative or specific humidity | \% or $kg/kg$ | 3 | 3-Hourly |
| Specific humidity | $kg/kg$ | 3 | 3-Hourly |
| Total aerosol mass | ${\mu}g/m^{3}$ | 3 | 3-Hourly |
| Rate of het. Br2 formation on all aerosols | $\# /cm^{3}/hour$ | 3 | 3-Hourly |


# Station locations for data interpolation
Model output should be interpolated in x/y/z/time. Results should also be provided  interpolated in x/y/time at the lowest model level (as a second time series), if possible.
| Station name      | Lat | Lon | Measurement altitute (meters ASL) |
| ----------- | ----------- | ---------------- | ---------  |
|Utqiagvik    | 71.323 |  -156.611 | 11 |
|Tiksi  | 71.58617 | 128.91823 | 10 |
|Summit | 72.578 | -38.459 | 3216 |
|Nord  | 81.600 | -16.670 | 20 |
|Alert | 82.49915 | -62.34153 | 210 |
|Zeppelin | 78.910  | 11.888 | 474 |
|Eureka | 79.9830 | -85.950 | 0 |

# Buoy locations for data interpolation - 2012
A text file with hourly locations of O-Buoy 4 and O-Buoy 6 is provided [here](O-buoys_track_B4_B6_Spring2012.txt) for models to interpolate data to their locations.

# Ship track location for data interpolation - 2020 
A text file with the hourly location of the MOSAiC expedition is provided [here](Shiptrack_Polarstern_MOSAiC_Spring2020.txt) for models to interpolate their data to the Polarstern location.

# Ozone sonde locations for data interpolation - 2012 and 2020
For models that keep subdaily 3D ozone data, text files with 3D location and time of ozone sonde profiles will be provided for modelers to interpolate data to their locations. 

# Satellite comparison
Models should plan to provide NetCDF files of model output to U. Bremen and they will compare the model fields to their satellite retrievals. Data should be provided on model levels. The following information is needed in the files:
 
- NetCDF dimensions: time, latitude, longitude, layers, levels
- NetCDF 4d-variables: BrO mixing ratio [ppbv] and temperature [K] at level centers, pressure [Pa] at level interfaces
- NetCDF 2(3)d-variable: surface altitude [m]
- NetCDF attributes: provider, model, version, creation_date

Pressure can also be provided in the form of surface pressure and hybrid coefficients.

Spatial and temporal resolution should be as high as possible. For satellite comparison, please save hourly output of these fields.

If you are planning to participate in the comparison to satellite data, please provide a small test file to Andreas Richter (richter@iup.physik.uni-bremen.de) to ensure that we can deal with the file format.
