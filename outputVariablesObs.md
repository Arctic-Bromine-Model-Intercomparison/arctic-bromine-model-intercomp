# Required model output variables
| Variable      | Unit | Dimensions | Frequency |
| ----------- | ----------- | ---------------- | ------------|
| Surface $O_3$ mixing ratio | ppbv | 2 | 3-Hourly |
| Surface BrO mixing ratio | ppbv | 2 | 3-Hourly |
| BrO mixing ratio | $ppbv$ | 3 | 3-Hourly |
| Surface sea salt aerosol mass concentration < 10 ${\mu}m$ diameter | $\mu g/m^{3}$ | 2 | 3-Hourly |
| 2-meter air temperature | K | 2 | 3-Hourly |
| Surface pressure | Pa | 2 | 3-Hourly |
| Air temperature | K | 3 | 3-Hourly |
| Air pressure | Pa | 3 | 3-Hourly |
| 10-m wind speed | m/s | 2 | 3-Hourly |
| Boundary layer height | m | 2 | 3-Hourly |
| Sea ice concentration | \% | 2 | Daily |
| $Br_2$ emissions| $moles/m^{2}$ | 2 | Daily |
| Sea salt aerosol emissions| $mg/m^{2}$ | 2 | Daily |
| Altitude of lowermost model level | m AGL + m ASL| - | - |

# Highly recommended model output
| Variable      | Unit | Dimensions | Frequency |
| ----------- | ----------- | ---------------- | ------------|
| $O_3$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| $Br_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| HOBr mixing ratio | $ppbv$ | 3 | 3-Hourly |
| HBr mixing ratio | $ppbv$ | 3 | 3-Hourly |
| ClO mixing ratio | $ppbv$ | 3 | 3-Hourly |
| $Cl_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| HOCl concentration | $ppbv$ | 3 | 3-Hourly |
| HCl mixing ratio | $ppbv$ | 3 | 3-Hourly |
| IO mixing ratio | $ppbv$ | 3 | 3-Hourly |
| $I_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| Sea salt aerosol mass concentration < 10 ${\mu}m$ | $\mu g/m^{3}$ | 3 | 3-Hourly |
| Sea salt aerosol number concentration < 10 ${\mu}m$ | \# $/m^{3}$ | 3 | 3-Hourly |
| OH mixing ratio | $ppbv$ | 3 | 3-Hourly |
| $HO_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly |
| NO mixing ratio | $ppbv$ | 3 | 3-Hourly |
| NO2 mixing ratio | $ppbv$ | 3 | 3-Hourly |
| $PM_{2.5}$ concentration | ${\mu}g/m^{3}$ | 3 | 3-Hourly |
| $PM_{10}$ concentration | ${\mu}g/m^{3}$ | 3 | 3-Hourly |
| Wind speed | $m/s$ | 3 | 3-Hourly |
| Wind direction | $^\circ$ | 3 | 3-Hourly |
| Relative humidity | \% | 3 | 3-Hourly |
| Specific humidity | $kg/kg$ | 3 | 3-Hourly |
| Boundary layer height | $m$ | 2 | 3-Hourly |
| Sea ice concentration | \% | 2 | Daily |
| $Br_2$ emissions from surface snow| $moles/m^{2}$ | 2 | Daily |
| $Br_2$ emissions from blowing snow| $moles/m^{2}$ | 2 | Daily |
| $Br_2$ emissions from sea spray| $moles/m^{2}$ | 2 | Daily |
| Sea salt aerosol emissions from blowing snow| $mg/m^{2}$ | 2 | Daily |
| Sea salt aerosol emissions from sea spray | $mg/m^{2}$ | 2 | Daily |

# Nice-to-have model output
| Variable      | Unit | Dimensions | Frequency |
| ----------- | ----------- | ---------------- | ------------|

# Station locations for data interpolation
| Station name      | Lat | Lon | Measurement altitute (meters ASL) |
| ----------- | ----------- | ---------------- | ---------  |
|Utqiagvik    | 71.323 |  -156.611 | 11 |
|Tiksi  | 71.586 | 128.919 | 8 |
|Summit | 72.578 | -38.459 | 3216 |
|Nord  | 81.600 | -16.670 | 20 |
|Alert | 82.499 | -62.341 | 210 |
|Zeppelin | 78.910  | 11.888 | 474 |


# Buoy locations for data interpolation - 2012
A text file with hourly locations of O-Buoy 4 and O-Buoy 6 will be provided for models to interpolate data to their locations.

# Ship track location for data interpolation - 2020 
A text file with the hourly location of the MOSAiC expedition will be provided for models to interpolate their data to the Polarstern location.

# Satellite comparison
Models should plan to provide netcdf files of BrO and other essential varaibles as netcdf files to U. Bremen and they will compare the models to their satellite retrievals.

