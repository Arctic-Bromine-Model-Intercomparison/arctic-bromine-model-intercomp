# Output Varibles that need to be saved

| Variable      | Unit | Dimensions | Frequency |
| ----------- | ----------- | ---------------- | ------------|
| Sea salt aerosol mass concentration  | $\mu g/m^{3}$ | 3 | Hourly |
| Sea salt aerosol number concentration  | \# $/m^{3}$ | 3 | Hourly |
| Wind speed and direction | $m/s$ | 3 | Hourly |
| Air temperature | $K$ | 3 | Hourly |
| Br mixing ratio | $ppbv$ | 3 | Hourly |
| BrO mixing ratio | $ppbv$ | 3 | Hourly |
| Br2 mixing ratio | $ppbv$ | 3 | Hourly |
| HOBr mixing ratio | $ppbv$ | 3 | Hourly |
| Cl concentration | $\mu g/m^{3}$ | 3 | Hourly |
| ClO concentration | $\mu g/m^{3}$ | 3 | Hourly |
| Cl2 concentration | $\mu g/m^{3}$ | 3 | Hourly |
| HOCl concentration | $\mu g/m^{3}$ | 3 | Hourly |
| O3 concentration | $ppbv$ | 3 | Hourly |
| Pressure | $Pa$ | 3 | Hourly |
| Relative humidity | \% | 3 | Hourly |
| Specific humidity | $kg/kg$ | 3 | Hourly |
| Sea surface temperature | $K$ | 2 | Hourly |
| Boundary layer height | $m$ | 2 | Hourly |
| Sea ice fraction | \% | 2 | Hourly |
| Sea salt aerosol mass emissions | $\mu g/m^{2}$ | 2 | Hourly |

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
A text file with hourly locations of O-Buoy 4 and O-Buoy 6 will be provided for models to interpolate data their locations.

# Ship track location for data interpolation - 2020 
A text file with the hourly locaiton of the MOSAiC expedition will be provided for models to interpolate their data to the Polarstern location.

# Satellite comparison
Models should plan to provide netcdf files of BrO, Temperature, Pressure, and relative humidity as netcdf files to U. Bremen and they will compare the models to their satellite retrievals.

