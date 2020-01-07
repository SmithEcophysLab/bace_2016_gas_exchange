# Metadata
Below are explanations of each of the variables found in the files contained in the [data](data)
folder.

## common variables
- **doy**: julian day of year
- **year**: year
- **plot**: plot in which measurement was taken
- **warming**: warming treatment, where 0 = no warming and 3 = high warming (1000 W/heater)
- **precipitation**: precipitation amount where 0 = ambient, -1 = reduced precipitation, and 1 = added precipitation
- **block**: block in which measurement was taken

## file-specific variables

### [canopy_temperatures.csv](data/canopy_temperatures.csv)
- **midday_canopy_temperature_mean**: mean canopy temperature over the hours of 10:00-16:00 (°C)

### [soil_moisture.csv](data/soil_moisture.csv)
- **REW**: relative extractable water (unitless value from 0-1)

### [gas_exchange.csv](data/gas_exchange.csv)
- **measurement_id**: unique identifier for the individual measurement
- **individual_id**: unique identifier for the plant measured
- **set_leaf_temperature**: leaf temperature set by the portable photosynthesis machine (°C)
- **measured_leaf_temperature**: leaf temperature measured by the thermocouple (°C)
- **measured_leaf_vpd**: leaf-to-air vapor pressure deficit measured by the portable photosynthesis machine (kPa)
- **measured_par**: photosynthetically active radiation measured by the portable photosynthesis machine (µmol m-2 s-1)
- **leaf_mass**: mass of the entire measured leaf (g)
- **leaf_area**: area of the entire measured leaf (cm2)
- **specific_leaf_area**: specific leaf area of the entire measured leaf (cm2/g)
- **vcmax**: maximum rate of Rubisco carboxylation at measured leaf temperature (µmol m-2 s-1)
- **jmax**: maximum rate of electron transport at measured leaf temperature (µmol m-2 s-1)
- **rd**: dark respiration rate at measured leaf temperature (µmol m-2 s-1)
- **l**: stomatal limitation parameter (unitless value from 0-1)