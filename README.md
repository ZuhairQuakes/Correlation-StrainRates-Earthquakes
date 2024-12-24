# Correlation Analysis of Strain Rates and Seismicity

This project demonstrates advanced geospatial data analysis by correlating strain rates with seismicity patterns to reveal insights into the tectonic behaviour of the Sagaing fault in Myanmar. It incorporates cutting-edge geospatial libraries and statistical methodologies to process and visualize data.

## Impact
This project provides a robust framework for geoscientists and data scientists to analyze strain rate-seismicity relationships, aiding in tectonic studies, seismic hazard assessment, and infrastructure planning in earthquake-prone regions.

## Key Features
- **Data Integration**: Analyzed strain rate data (NetCDF format) and seismic event catalogs (CSV format) using Python libraries such as `netCDF4`, `Pandas`, and `Geopandas`.
- **Advanced Visualization**: Created insightful visualizations with `Cartopy` and `Matplotlib`, including spatial overlays of seismicity and strain rates.
- **Fault Analysis**: Processed and segmented fault line data to study active tectonic features, focusing on the Sagaing Fault system.
- **Geospatial Interpolation**: Utilized `Scipy`'s `griddata` and Gaussian smoothing to interpolate and refine strain rate data.
- **Dynamic Mapping**: Exported geospatial data in KML format for interactive exploration in GIS tools.

## Technologies Used
- **Programming Languages**: Python
- **Libraries**: `netCDF4`, `Pandas`, `Geopandas`, `Cartopy`, `Scipy`, `Matplotlib`
- **Data Formats**: NetCDF, CSV, Shapefiles, KML
- **Geospatial Tools**: Fault segmentation, strain rate interpolation, and seismicity overlay
