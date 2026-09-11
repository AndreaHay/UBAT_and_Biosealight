# UBAT and Biosealight
Data and python scripts supporting submitted manuscript comparing UBAT and Biosealight bioluminescence observations

# Data
NetCDF files containing the following data:
-  smooth_profiles.nc: profiles of UBAT and Biosealight bioluminescence intensity
-  flash_density_profiles.nc: profiles of UBAT and Biosealight flash density
-  ubat_extracted_flashes.nc: all extracted flashed from UBAT data
-  cem_extracted_flashes.nc: all extracted flashed from Biosealight data
-  vertical_velocity.nc: glider absolute vertical velocity profiles calculated from pressure and time

# Notebooks
Jupyter notebooks with analysis to produce the following figures in the accompanying manuscript
- profile_comparison.ipynb: bioluminescence profile comparison results shown in figures 3 and 4
- flash_duration_distribution.ipynb: bioluminescence flash duration comparison results shown in figure 5
- example_Aug18.ipynb: bioluminescence and velocity profiles during August 18 shown in figure 6
- velocity_impact.ipynb: assessment of the impact of glider vertical velocity on flash density shown in figure 7
