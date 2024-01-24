# Required model output variables
The absolute minimal results to provide in the intercomparison are the following:
- 3-hourly 2D/3D variables in the table below, interpolated along relevant observation stations and campaigns
- 3-hourly 3D BrO,T,P data in the table below, processed appropriately for comparison to satellite BrO observations
- Daily 2D variables from the table below.

We strongly recommend that all the full 2D/3D/4D fields in the table below are saved, so that interpolations and analysis can be redone in case of errors.

| Variable      | Unit | Dimensions | Frequency | name in file |
| ----------- | ----------- | ---------------- | ------------| ------------|
| Surface $O_3$ mixing ratio | ppbv | 3 | 3-Hourly | O3_surface_ppbv |
| Surface BrO mixing ratio | ppbv | 3 | 3-Hourly | BrO_surface_ppbv |
| Surface dry sea salt aerosol mass concentration < 10 ${\mu}m$ diameter | $\mu g/m^{3} (ambient)$ | 3 | 3-Hourly | SSA_surface_PM10_mass |
| 2-meter air temperature | K | 3 | 3-Hourly | T2_K |
| Surface pressure | Pa | 3 | 3-Hourly | PSurf_Pa |
| 10-m wind speed | m/s | 3 | 3-Hourly | W10_m_s |
| Boundary layer height | m | 3 | 3-Hourly | PBLH_m |
| BrO mixing ratio  | $ppbv$ | 4 | 3-Hourly | BrO_ppbv |
| Air temperature | K | 4 | 3-Hourly | T_K |
| Air pressure  | Pa | 4 | 3-Hourly | P_Pa |
| Sea ice concentration | \% | 3 | 3-Hourly | frac_sea_ice |
| $Br_2$ emissions| $moles/m^{2}/hour$ | 3 | 3-Hourly | Br2_emiss_mol_m2_hour |
| Sea salt aerosol emissions| $mg/m^{2}/hour$ | 3 | 3-Hourly | SSA_emiss_mg_m2_hour |
| Altitude of lowermost model level | m AGL + m ASL| 2 | - | Alt_lev0_m |

In addition, the following information should be saved:
- Model grid dimensions: time, latitude, longitude, layers, levels
- Model information/attributes: provider, model, version, creation_date

# Highly recommended model output
If some of these variables cannot be saved by your model, saving some is better than none!
| Variable      | Unit | Dimensions | Frequency | name in file |
| ----------- | ----------- | ---------------- | ------------| ------------|
| $O_3$ mixing ratio | $ppbv$ | 4 | 3-Hourly | O3_ppbv |
| Sea salt aerosol mass concentration < 10 ${\mu}m$ | $\mu g/m^{3}$ | 4 | 3-Hourly | SSA_PM10_mass |
| Sea salt aerosol number concentration < 10 ${\mu}m$ | \# $/m^{3}$ | 4 | 3-Hourly | SSA_PM10_number |
| $PM_{2.5}$ mass  | ${\mu}g/m^{3}$ | 4 | 3-Hourly | PM25_mass |
| $PM_{10}$  mass | ${\mu}g/m^{3}$ | 4 | 3-Hourly | PM10_mass |
| Total aerosol mass | ${\mu}g/m^{3}$ | 4 | 3-Hourly | PM_mass |
| Surface Wind speed | $m/s$ | 3 | 3-Hourly | WS_surface_m_s |
| Surface Wind direction | $^\circ$ | 3 | 3-Hourly | WD_surface |
| Surface Relative or specific humidity | \% or $kg/kg$ | 3 | 3-Hourly | RH_surface |
| Surface $Br_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly | Br2_surface_ppbv |
| Surface OH mixing ratio | $ppbv$ | 3 | 3-Hourly | OH_surface_ppbv |
| Surface $HO_2$ mixing ratio | $ppbv$ | 3 | 3-Hourly | HO2_surface_ppbv |
| $Br_2$ emissions from surface snow | $moles/m^{2}$ | 3 | 3-Hourly | Br2_emiss_surface |
| $Br_2$ emissions from blowing snow | $moles/m^{2}$ | 3 | 3-Hourly | Br2_emiss_bs |
| $Br_2$ emissions from sea spray | $moles/m^{2}$ | 3 | 3-Hourly | Br2_emiss_SSA |
| Sea salt aerosol emissions from blowing snow| $mg/m^{2}$ | 3 | 3-Hourly | SSA_emiss_bs |
| Sea salt aerosol emissions from sea spray | $mg/m^{2}$ | 3 | 3-Hourly | SSA_emiss_ss |

# Nice-to-have model output
If some of these variables cannot be saved by your model, saving some is better than none!
| Variable      | Unit | Dimensions | Frequency | name in file |
| ----------- | ----------- | ---------------- | ------------| ------------|
| $Br_2$ mixing ratio | $ppbv$ | 4 | 3-Hourly | Br2_ppbv |
| OH mixing ratio | $ppbv$ | 4 | 3-Hourly | OH_ppbv |
| $HO_2$ mixing ratio | $ppbv$ | 4 | 3-Hourly | HO2_ppbv |
| HOBr mixing ratio | $ppbv$ | 4 | 3-Hourly | HOBr_ppbv |
| HBr mixing ratio | $ppbv$ | 4 | 3-Hourly | HBr_ppbv |
| ClO mixing ratio | $ppbv$ | 4 | 3-Hourly | ClO_ppbv |
| $Cl_2$ mixing ratio | $ppbv$ | 4 | 3-Hourly | Cl2_ppbv |
| HOCl concentration | $ppbv$ | 4 | 3-Hourly | HOCl_ppbv |
| HCl mixing ratio | $ppbv$ | 4 | 3-Hourly | HCl_ppbv |
| IO mixing ratio | $ppbv$ | 4 | 3-Hourly | IO_ppbv |
| $I_2$ mixing ratio | $ppbv$ | 4 | 3-Hourly | I2_ppbv |
| NO mixing ratio | $ppbv$ | 4 | 3-Hourly | NO_ppbv |
| NO2 mixing ratio | $ppbv$ | 4 | 3-Hourly | NO2_ppbv |
| Wind speed | $m/s$ | 4 | 3-Hourly | WS |
| Wind direction | $^\circ$ | 4 | 3-Hourly | WD |
| Relative humidity | \% or $kg/kg$ | 4 | 3-Hourly | RH |
| Specific humidity | $kg/kg$ | 4 | 3-Hourly | Q |
| Total aerosol mass | ${\mu}g/m^{3}$ | 4 | 3-Hourly | PM_mass |
| Rate of het. Br2 formation on all aerosols | \# $/cm^{3}/hour$ | 4 | 3-Hourly | Br2_rate |


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
