### Sentinel-5P monthly tropospheric nitrogen dioxide density

- 🔗 URL: https://stac.openlandmap.org/no2_s5p.l3.trop.tmwm/collection.json
- 📰 Description: Nitrogen Dioxide Density monthly median value May 2018 – November 2022. Derived using the [eumap package in Python](https://eumap.readthedocs.io). We derived three standard statistics: (1) 10th percentile (p10), median (m), and 90th percentile (p10).
- 📝 Theme: Orthoimagery
- 📂 DOI: https://doi.org/10.5281/zenodo.7464099

### Sentinel-5P long-term tropospheric nitrogen dioxide density

- 🔗 URL: https://stac.openlandmap.org/no2_s5p.l3.trop.tmwm.ltm/collection.json
- 📰 Description: Nitrogen Dioxide Density long term quantile from monthly median value May 2018 – November 2022. Derived using the [eumap package in Python](https://eumap.readthedocs.io). We derived three standard statistics: (1) 10th percentile (p10), median (m), and 90th percentile (p10).
- 📝 Theme: Orthoimagery
- 📂 DOI: https://doi.org/10.5281/zenodo.7464099

### OpenLandMap annual soil organic carbon

- 🔗 URL: https://stac.openlandmap.org/log.oc_iso.10694/collection.json
- 🗞 Description: Log organic carbon [g/kg] predicted at various soil depths
- 📝 Theme: Geology and Soils
- 📂 DOI: 

### MOD13Q1 long-term Enhanced Vegetation Index (EVI - trend analysis)

- 🔗 URL: https://stac.openlandmap.org/evi_mod13q1.stl.trend.logit.ols.beta/collection.json
- 📰 Description: Analysis-ready EVI trend component based on MOD13Q1 by every two months and fully gapfilled. The trend component was derived by [Season-Trend decomposition using LOESS](https://www.statsmodels.org/dev/generated/statsmodels.tsa.seasonal.STL.html#statsmodels.tsa.seasonal.STL).
- 📝 Theme: Orthoimagery
- 📂 DOI: 

### ESA CCI annual land cover

- 🔗 URL: https://stac.openlandmap.org/land.cover_esacci.lc.l4/collection.json
- 📰 Description: Based on the European Space Agency (ESA) Climate Change Initiative (ESACCI-LC).
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: 

### MOD13Q1 bi-monthly Enhanced Vegetation Index Index (EVI)

- 🔗 URL: https://stac.openlandmap.org/evi_mod13q1.tmwm.inpaint/collection.json
- 🗞 Description: Analysis-ready EVI based on MOD13Q1 aggregated by every two months, according to the percentile 90th, and fully gapfilled. The gapfilling was based in 1) [Temporal Moving Window Median](https://eumap.readthedocs.io/en/latest/_autosummary/eumap.gapfiller.TMWM.html#eumap.gapfiller.TMWM) algorithm, and 2) [inpating](https://eumap.readthedocs.io/en/latest/_autosummary/eumap.gapfiller.InPainting.html) technique.
- 📝 Theme: Orthoimagery
- 📂 DOI: 

### OpenLandMap ensemble digital terrain model

- 🔗 URL: https://stac.openlandmap.org/dtm.bareearth_ensemble/collection.json
- 📰 Description: Derived using ALOS AW3D, GLO-30, MERITDEM, and national DTMs, considering the lower 10% quantile from all input layers. In order to create bare earth data, we used canopy height (canopy height > 2m) and standard deviation (sd > 6m) to mask building and forest in AW3D and GLO-30. 
- 📝 Theme: Elevation and Depth
- 📂 DOI: https://doi.org/10.5281/zenodo.7676373

### Monthly fraction of absorbed photosynthetically active radiation (FAPAR)

- 🔗 URL: https://stac.openlandmap.org/fapar_essd.lstm/collection.json
- 📰 Description: The monthly aggregated Fraction of Absorbed Photosynthetically Active Radiation (FAPAR) dataset is derived from 250m 8d GLASS V6 FAPAR, considering several other FAPAR products (MODIS Collection 6, GLASS FAPAR V5, and PROBA-V1 FAPAR) to generate a bidirectional long-short-term memory (Bi-LSTM) model to adjust and harmonize FAPAR across two decades. The monthly aggregation includes three standard statistics: (1) 5th percentile (p05), median (p50), and 95th percentile (p95). For each month, we aggregate all composites within that month plus one composite each before and after, ending up with 5 to 6 composites for a single month depending on the number of images within that month.
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.8408654

### Long-term fraction of absorbed photosynthetically active radiation (FAPAR - trend analysis)

- 🔗 URL: https://stac.openlandmap.org/fapar_essd.lstm.p95.beta/collection.json
- 📰 Description: The monthly aggregated Fraction of Absorbed Photosynthetically Active Radiation (FAPAR) dataset is derived from 250m 8d GLASS V6 FAPAR, considering several other FAPAR products (MODIS Collection 6, GLASS FAPAR V5, and PROBA-V1 FAPAR) to generate a bidirectional long-short-term memory (Bi-LSTM) model to adjust and harmonize FAPAR across two decades. The trend analysis provides OLS model for the p95 time-series including: (1) slope beta mean (p95.beta_m), p-value for beta (p95.beta_pv), intercept alpha mean (p95.alpha_m), p-value for alpha (p95.alpha_pv), and coefficient of determination R2 (p95.r2_m).
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.8399173

### Annual potential fraction of absorbed photosynthetically active radiation (FAPAR - 2021)

- 🔗 URL: https://stac.openlandmap.org/pot.fapar_fapar.p95.eml.m/collection.json
- 🗞 Description: Potential FAPAR predicted by fitting an ensemble ML model using globally distributed training points (cca 3 Mio) and a set of 52 biophysical covariates including several layers related to human pressure. The spatial layers include 1) yearly average of potential FAPAR + model deviance, 2) yearly average of FAPAR (P50). 
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.8404153

### Monthly potential fraction of absorbed photosynthetically active radiation (FAPAR - 2021)

- 🔗 URL: https://stac.openlandmap.org/pot.fapar_fapar.p95.eml/collection.json
- 🗞 Description: Potential FAPAR predicted every month, in 2021, by fitting an ensemble ML model using globally distributed training points (cca 3 Mio) and a set of 52 biophysical covariates including several layers related to human pressure. 
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.8404153

### ESA monthly snow cover fraction

- 🔗 URL: https://stac.openlandmap.org/snow.cover_esa.modis/collection.json
- 📰 Description: Global MODIS-based snow cover monthly long-term (2000-2012) at 500 m. Global snow cover monthly long-term (2000–2012) P90 and standard deviation derived from the ESA CCI snow cover weekly product.
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.5281/zenodo.5774953

### ESA long-term snow cover fraction

- 🔗 URL: https://stac.openlandmap.org/snow.cover_esa.modis.ltm/collection.json
- 📰 Description: Global MODIS-based snow cover monthly long-term (2000-2012) at 500 m. Global snow cover monthly long-term (2000–2012) P90 and standard deviation derived from the ESA CCI snow cover weekly product.
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.5281/zenodo.5774953

### Annual terrestrial human footprint

- 🔗 URL: https://stac.openlandmap.org/wilderness_li2022.human.footprint/collection.json
- 📰 Description: Dataset of annual dynamics of the global Human Footprint from 2000 to 2018 using eight variables that reflect different aspects of human pressures.
- 📝 Theme: Population Distribution
- 📂 DOI: https://doi.org/10.1038/s41597-022-01284-8

### MCD19A2 monthly water vapor

- 🔗 URL: https://stac.openlandmap.org/wv_mcd19a2v061.seasconv/collection.json
- 📰 Description: The monthly aggregated water vapor dataset is derived from MCD19A2 v061, measuring the column above ground retrieved from MODIS near-IR bands at 0.94μm. The dataset time spans from 2000 to 2022 and provides data that covers the entire globe. The monthly aggregation considered the mean and standard deviation of daily water vapor time-series data. Only positive non-cloudy pixels were considered valid observations to derive the mean and the standard deviation. The remaining no-data values were filled using the TMWM algorithm. This dataset also includes smoothed mean and standard deviation values using the Whittaker method. The quality assessment layers and the number of valid observations for each month can provide an indication of the reliability of the monthly mean and standard deviation values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.8226283

### MCD19A2 long-term water vapor (perc. 50th)

- 🔗 URL: https://stac.openlandmap.org/wv_mcd19a2v061.seasconv.m_p50/collection.json
- 🗞 Description: The monthly aggregated water vapor dataset is derived from MCD19A2 v061, measuring the column above ground retrieved from MODIS near-IR bands at 0.94μm. The dataset time spans from 2000 to 2022 and provides data that covers the entire globe. The monthly aggregation considered the mean and standard deviation of daily water vapor time-series data. Only positive non-cloudy pixels were considered valid observations to derive the mean and the standard deviation. The remaining no-data values were filled using the TMWM algorithm. This dataset also includes smoothed mean and standard deviation values using the Whittaker method. The quality assessment layers and the number of valid observations for each month can provide an indication of the reliability of the monthly mean and standard deviation values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.8226283

### MCD19A2 long-term water vapor (perc. 25th)

- 🔗 URL: https://stac.openlandmap.org/wv_mcd19a2v061.seasconv.m_p25/collection.json
- 📰 Description: The monthly aggregated water vapor dataset is derived from MCD19A2 v061, measuring the column above ground retrieved from MODIS near-IR bands at 0.94μm. The dataset time spans from 2000 to 2022 and provides data that covers the entire globe. The monthly aggregation considered the mean and standard deviation of daily water vapor time-series data. Only positive non-cloudy pixels were considered valid observations to derive the mean and the standard deviation. The remaining no-data values were filled using the TMWM algorithm. This dataset also includes smoothed mean and standard deviation values using the Whittaker method. The quality assessment layers and the number of valid observations for each month can provide an indication of the reliability of the monthly mean and standard deviation values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.8226283

### MCD19A2 long-term water vapor (perc. 75th)

- 🔗 URL: https://stac.openlandmap.org/wv_mcd19a2v061.seasconv.m_p75/collection.json
- 📰 Description: The monthly aggregated water vapor dataset is derived from MCD19A2 v061, measuring the column above ground retrieved from MODIS near-IR bands at 0.94μm. The dataset time spans from 2000 to 2022 and provides data that covers the entire globe. The monthly aggregation considered the mean and standard deviation of daily water vapor time-series data. Only positive non-cloudy pixels were considered valid observations to derive the mean and the standard deviation. The remaining no-data values were filled using the TMWM algorithm. This dataset also includes smoothed mean and standard deviation values using the Whittaker method. The quality assessment layers and the number of valid observations for each month can provide an indication of the reliability of the monthly mean and standard deviation values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.8226283

### MCD19A2 long-term water vapor (std. dev.)

- 🔗 URL: https://stac.openlandmap.org/wv_mcd19a2v061.seasconv.m_std/collection.json
- 🗞 Description: The monthly aggregated water vapor dataset is derived from MCD19A2 v061, measuring the column above ground retrieved from MODIS near-IR bands at 0.94μm. The dataset time spans from 2000 to 2022 and provides data that covers the entire globe. The monthly aggregation considered the mean and standard deviation of daily water vapor time-series data. Only positive non-cloudy pixels were considered valid observations to derive the mean and the standard deviation. The remaining no-data values were filled using the TMWM algorithm. This dataset also includes smoothed mean and standard deviation values using the Whittaker method. The quality assessment layers and the number of valid observations for each month can provide an indication of the reliability of the monthly mean and standard deviation values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.8226283

### MCD19A2 annual water vapor

- 🔗 URL: https://stac.openlandmap.org/wv_mcd19a2v061.seasconv.m.yearly/collection.json
- 🗞 Description: The monthly aggregated water vapor dataset is derived from MCD19A2 v061, measuring the column above ground retrieved from MODIS near-IR bands at 0.94μm. The dataset time spans from 2000 to 2022 and provides data that covers the entire globe. The monthly aggregation considered the mean and standard deviation of daily water vapor time-series data. Only positive non-cloudy pixels were considered valid observations to derive the mean and the standard deviation. The remaining no-data values were filled using the TMWM algorithm. This dataset is specifically derived from monthly time-series, providing a yearly time-series aggregated statistics of the monthly time-series data.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.8226282

### Long-term soil bulk density for fine earth

- 🔗 URL: https://stac.openlandmap.org/bulkdens.fineearth_usda.4a1h/collection.json
- 📰 Description: Soil bulk density (fine earth) 10 x kg / m-cubic at 6 standard depths (0, 10, 30, 60, 100 and 200 cm) at 250 m resolution
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.2525665

### MERIT geomorphometry

- 🔗 URL: https://stac.openlandmap.org/geom_merit.dem/collection.json
- 📰 Description: Relief parameters were derived derived using SAGA GIS (http://www.saga-gis.org/) and the MERIT DEM (Yamazaki et al. 2017) projected in the Equi7 grid system (Bauer-Marschallinger et al. 2014). Once derived, DEM derivatives were then reprojected to the lon-lat system.
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.1038/s41597-020-0479-6

### PROBA-V long-term fraction of absorbed photosynthetically active radiation (FAPAR)

- 🔗 URL: https://stac.openlandmap.org/fapar_proba.v/collection.json
- 🗞 Description: Fraction of absorbed photosynthetically active radiation monthly images for 2014–2017 were obtained from https://land.copernicus.eu (original values reported in the range 0–235 with scaling factor 1/255, i.e., with a maximum value of 0.94). From a total of 142 images downloaded from https://land.copernicus.eu we derived minimum, median and maximum value of FAPAR per month (12) using the 95% probability interval using the data.table package (http://r-datatable.com).
- 📝 Theme: Orthoimagery
- 📂 DOI: https://doi.org/10.5281/zenodo.3459830

### Tree-covered and intact forest landscapes

- 🔗 URL: https://stac.openlandmap.org/forest.cover_esacci.ifl/collection.json
- 📰 Description: Based on the UNEP historic forest cover map, ESA land cover time series and intact forest landscape (IFL 2000, 2013 and 2016) data (Potapov et al. 2013).
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.5281/zenodo.1477073

### USDA long-term soil great groups

- 🔗 URL: https://stac.openlandmap.org/grtgroup_usda.soiltax/collection.json
- 📰 Description: Distribution of the USDA soil great groups based on machine learning predictions from global compilation of soil profiles (>350,000 training points).
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.3528062

### Copernicus PROBA-V annual land cover

- 🔗 URL: https://stac.openlandmap.org/land.cover_copernicus/collection.json
- 📰 Description: Annual, global 100m land cover maps in 2015, 2016, 2017, 2018, 2019, produced by the global component of the Copernicus Land Service, derived from PROBA-V satellite observations and ancillary datasets
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.5281/zenodo.4723924

### OpenLandMap long-term soil organic carbon stock

- 🔗 URL: https://stac.openlandmap.org/organic.carbon.stock_msa.kgm2/collection.json
- 🗞 Description: Soil organic carbon stock in kg/m2 for 5 standard depth intervals (0–10, 10–30, 30–60, 60–100 and 100–200 cm) at 250 m resolution. To convert to t/ha multiply by 10. Derived using soil organic carbon content (https://doi.org/10.5281/zenodo.1475457), bulk density (https://doi.org/10.5281/zenodo.1475970) and coarse fragments (https://doi.org/10.5281/zenodo.2525681), predicted from point data at 6 standard depths. Depth to bed rock has been ignored, hence total stocks might be about 10–15% lower then reported.
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.2536040

### OpenLandMap long-term soil organic carbon content

- 🔗 URL: https://stac.openlandmap.org/organic.carbon_usda.6a1c/collection.json
- 📰 Description: Soil organic carbon content in x 5 g / kg (to convert to % divide by 2) at 6 standard depths (0, 10, 30, 60, 100 and 200 cm) at 250 m resolution.Predicted from a global compilation of soil points. Also available for download: soil organic stock maps in in kg / m2 (https://doi.org/10.5281/zenodo.1475453) and bulk density maps in kg / m3 (https://doi.org/10.5281/zenodo.1475970).
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.2525553

### ESA CCI annual plant functional types (PFT)

- 🔗 URL: https://stac.openlandmap.org/pft.landcover_esa.cci.lc/collection.json
- 🗞 Description: This dataset contains Global Plant Functional Types (PFT) data, from the ESA Medium Resolution Land Cover (MRLC) Climate Change Initiative project. The data provides yearly data, and initially covers the time period from 1992 to 2020. It is anticipated that the dataset will be updated annually going forward. The PFT v2.0.8 global dataset has 14 layers, each describing the percentage cover (0-100%) of a plant functional type at a spatial resolution of 300 m: broadleaved evergreen trees, broadleaved deciduous trees, needleleaved evergreen trees, needleleaved deciduous trees, broadleaved evergreen shrubs, broadleaved deciduous shrubs, needleleaved evergreen shrubs, needleleaved deciduous shrubs, natural grasses, herbaceous cropland (i.e., managed grasses), built, water, bare areas, and snow and ice.
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.5285/26a0f46c95ee4c29b5c650b129aab788

### SM2RAIN long-term precipitation

- 🔗 URL: https://stac.openlandmap.org/precipitation_sm2rain.ltm/collection.json
- 🗞 Description: Monthly precipitation in mm at 1 km resolution based on SM2RAIN-ASCAT 2007-2021 (https://doi.org/10.5281/zenodo.2615278). Downscaled to 1 km resolution using gdalwarp (cubic splines) and combined with WorldClim (https://worldclim.org/data/worldclim21.html) and CHELSA Climate (https://chelsa-climate.org/downloads/) monthly values. Final values are estimated as a simple average between the three precipitation data sources; a more objective approach would be to use training points e.g. meteo-station monthly values, then train an ensemble model using the 3 data sources as independent variables. Another global data source of precipitation images is the monthly IMERGE dataset, however this requires transformation and is available only for limited span of years.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.6458580

### OpenLandMap long-term soil pH

- 🔗 URL: https://stac.openlandmap.org/ph.h2o_usda.4c1a2a/collection.json
- 📰 Description: Soil pH in H2O at 6 standard depths (0, 10, 30, 60, 100 and 200 cm) at 250 m resolution according to USDA method code: 4C1a2a
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.2525664

### JRC Global Human Settlement annual population (GHS)

- 🔗 URL: https://stac.openlandmap.org/pop.count_ghs.jrc/collection.json
- 📰 Description: This GHS-POP spatial raster product (GHS-POP_GLOBE_R2023) depicts the distribution of human population, expressed as the number of people per cell. Residential population estimates at 5 years interval between 1975 and 2030 are derived from the raw global census data harmonized by CIESIN for the Gridded Population of the World, version 4.11 (GPWv4.11) at polygon level, and disaggregated from census or administrative units to grid cells, informed by the distribution, classification and volume of built-up as mapped in the GHSL global layers per corresponding epoch. The disaggregation methodology is described in Freire et al., (2016).
- 📝 Theme: Population Distribution
- 📂 DOI: https://doi.org/10.2905/2FF68A52-5B5B-4A22-8F40-C41DA8332CFE

### OpenLandMap long-term sand content

- 🔗 URL: https://stac.openlandmap.org/sand.wfraction_usda.3a1a1a/collection.json
- 🗞 Description: Sand content in % (kg / kg) at 6 standard depths (0, 10, 30, 60, 100 and 200 cm) at 250 m resolution. Based on machine learning predictions from global compilation of soil profiles and samples.
- 📝 Theme: Water
- 📂 DOI: https://doi.org/10.5281/zenodo.2525662

### MCD12Q1 annual land cover and land use

- 🔗 URL: https://stac.openlandmap.org/lc_mcd12q1v061.p1/collection.json
- 🗞 Description: The yearly land use and land cover dataset is derived from MCD12Q1 v061. This data provides an yearly mosaics of land use and land cover data from 2001 to 2022. This dataset includes layers of land cover type 1 (t1), 2 (t2), and 5 (t5), land cover property 1 (p1) and 2 (p2), land cover property assessment 1 (p1a) and 2 (p2a), and land cover quality control (qc).
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.5281/zenodo.8367523

### OpenLandMap long-term soil texture classes (USDA system)

- 🔗 URL: https://stac.openlandmap.org/texture.class_usda.tt/collection.json
- 🗞 Description: Soil texture classes (USDA system) for 6 standard soil depths (0, 10, 30, 60, 100 and 200 cm) at 250 m.
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.2525817

### JRC long-term surface water occurrence

- 🔗 URL: https://stac.openlandmap.org/water.occurrence_jrc.surfacewater/collection.json
- 📰 Description: Gobal surface water occurrence based on Pekel at al. (2016), and the layer is resampled to spatial resolution 1/480 d.d. (about 250 m) using gdalwarp with "average" resampling. Original layers are available at 30 m resolution. The orignal dataset and document: https://doi.org/10.1038/nature20584.
- 📝 Theme: Water
- 📂 DOI: https://doi.org/10.5281/zenodo.1439254

### OpenLandMap long-term soil water content

- 🔗 URL: https://stac.openlandmap.org/watercontent.33kPa_usda.4b1c/collection.json
- 📰 Description: Soil water content (volumetric) in percent for 33 kPa and 1500 kPa suctions predicted at 6 standard depths (0, 10, 30, 60, 100 and 200 cm) at 250 m resolution. Training points are based on a global compilation of soil profiles (USDA NCSS, AfSPDB, ISRIC WISE, EGRPR, SPADE, CanNPDB, UNSODA, SWIG, HYBRAS and HydroS). Data import steps are available here. Spatial prediction steps are described in detail here. Note: these are actually measured and mapped soil content values; no Pedo-Transfer-Functions have been used (except to fill-in the missing NCSS bulk densities). Available water capacity in mm (derived as a difference between field capacity and wilting point multiplied by layer thickness) per layer is available here. Antarctica is not included.
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.2784001

### Copernius DEM digital surface model

- 🔗 URL: https://stac.openlandmap.org/dsm_glo30/collection.json
- 🗞 Description: Global mosaic of 30m Copernicus DEM. The Copernicus DEM is a Digital Surface Model (DSM) that represents the surface of the Earth including buildings, infrastructure and vegetation. Data were acquired through the TanDEM-X mission between 2011 and 2015. 
- 📝 Theme: Elevation and Depth
- 📂 DOI: https://doi.org/10.5270/ESA-c5d3d65

### UMD GLAD annual land cover and land use (GLCLUC)

- 🔗 URL: https://stac.openlandmap.org/lc_glad.glcluc/collection.json
- 📰 Description: The global 30-m spatial resolution dataset quantifies changes in forest extent and height, cropland, built-up lands, surface water, and perennial snow and ice extent from the year 2000 to 2020. Landsat Analysis Ready Data served as an input for land cover and use mapping. Each thematic product was independently derived using locally and regionally calibrated machine learning tools.
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.3389/frsen.2022.856903

### UMD GLAD annual land cover and land use change (GLCLUC)

- 🔗 URL: https://stac.openlandmap.org/lc_glad.glcluc.change/collection.json
- 📰 Description: The global 30-m spatial resolution dataset quantifies changes in forest extent and height, cropland, built-up lands, surface water, and perennial snow and ice extent from the year 2000 to 2020. Landsat Analysis Ready Data served as an input for land cover and use mapping. Each thematic product was independently derived using locally and regionally calibrated machine learning tools.
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.3389/frsen.2022.856903

### HYDE annual cropland for the holocene

- 🔗 URL: https://stac.openlandmap.org/landuse.cropland_hyde/collection.json
- 🗞 Description: History Database of the Global Environment (HYDE version 3.2). HYDE is an internally consistent combination of historical population estimates and allocation algorithms with time-dependent weighting maps for land use.
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.17026/dans-25g-gez3

### HYDE annual pasture for the holocene

- 🔗 URL: https://stac.openlandmap.org/landuse.pasture_hyde/collection.json
- 📰 Description: History Database of the Global Environment (HYDE version 3.2). HYDE is an internally consistent combination of historical population estimates and allocation algorithms with time-dependent weighting maps for land use.
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.17026/dans-25g-gez3

### HILDA+ annual land use and land cover change

- 🔗 URL: https://stac.openlandmap.org/land.use.land.cover_hilda.plus/collection.json
- 🗞 Description: HILDA+ (HIstoric Land Dynamics Assessment+) global dataset indicates annual land use/cover change between 1960-2019 at 1 km spatial resolution. It integrates multiple open data streams (from high-resolution remote sensing, long-term land use reconstructions and statistics). It covers six generic land use/cover categories: 1: Urban areas, 2: Cropland, 3: Pasture/rangeland, 4: Forest, 5: Unmanaged grass/shrubland, 6: Sparse/no vegetation.
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.1594/PANGAEA.921846

### MOD11A2 long-term land surface temperature trend (daytime)

- 🔗 URL: https://stac.openlandmap.org/lst_mod11a2.daytime.trend.logit.ols.beta/collection.json
- 📰 Description: Long-term trend analysis of MOD11A2 monthly LST day-time temperatures. Trend was produced by fitting regression models to de-seasonalized time-series. Models are fitted for each pixel and several long-term temporal metrics (alpha, beta, P>|t|, rsqr) has been derived.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.1420114

### MOD11A2 long-term land surface temperature trend (nighttime)

- 🔗 URL: https://stac.openlandmap.org/lst_mod11a2.nighttime.trend.logit.ols.beta/collection.json
- 🗞 Description: Long-term trend analysis of MOD11A2 monthly LST night-time temperatures. Trend was produced by fitting regression models to de-seasonalized time-series. Models are fitted for each pixel and several long-term temporal metrics (alpha, beta, P>|t|, rsqr) has been derived.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.1420114

### MOD11A2 annual land surface temperature (day-time)

- 🔗 URL: https://stac.openlandmap.org/lst_mod11a2.daytime.annual/collection.json
- 📰 Description: Day-time land surface temperature, derived from MOD11A2, yearly aggregated considering three percentiles (p05, p50 and p95) and standard deviation of cloud-free pixels. All months were gapfilled by TMWM, which uses cloud-free pixel values from diferent periods to interpolate the missing values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.1420114

### MOD11A2 annual land surface temperature (night-time)

- 🔗 URL: https://stac.openlandmap.org/lst_mod11a2.nighttime.annual/collection.json
- 🗞 Description: Night-time land surface temperature, derived from MOD11A2, yearly aggregated considering three percentiles (p05, p50 and p95) and standard deviation of cloud-free pixels. All months were gapfilled by TMWM, which uses cloud-free pixel values from diferent periods to interpolate the missing values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.1420114

### MOD11A2 monthly land surface temperature (day-time)

- 🔗 URL: https://stac.openlandmap.org/lst_mod11a2.daytime/collection.json
- 🗞 Description: Day-time land surface temperature, derived from MOD11A2, monthly aggregated considering three percentiles (p05, p50 and p95) and standard deviation of cloud-free pixels. All months were gapfilled by TMWM, which uses cloud-free pixel values from diferent periods to interpolate the missing values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.1420114

### MOD11A2 monthly land surface temperature (night-time)

- 🔗 URL: https://stac.openlandmap.org/lst_mod11a2.nighttime/collection.json
- 📰 Description: Night-time land surface temperature, derived from MOD11A2, monthly aggregated considering three percentiles (p05, p50 and p95) and standard deviation of cloud-free pixels. All months were gapfilled by TMWM, which uses cloud-free pixel values from diferent periods to interpolate the missing values.
- 📝 Theme: Climate
- 📂 DOI: https://doi.org/10.5281/zenodo.1420114

### OpenLandMap landform classes

- 🔗 URL: https://stac.openlandmap.org/landform_usgs.ecotapestry/collection.json
- 🗞 Description: Layers include: landform (7) indicator maps (0-100%). Derived from the USGS Global Ecosystem Map, i.e. the EcoTapestry map. Water bodies masked out. Antarctica is not included.
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.1464846

### OpenLandMap lithology classes

- 🔗 URL: https://stac.openlandmap.org/lithology_usgs.ecotapestry/collection.json
- 📰 Description: Layers include: lithology (15) indicator maps (0-100%). Derived from the USGS Global Ecosystem Map, i.e. the EcoTapestry map. Water bodies masked out. Antarctica is not included.
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.1464846

### OpenLandMap Haopludalfs of USDA soil great groups

- 🔗 URL: https://stac.openlandmap.org/grtgroup_usda.soiltax.hapludalfs/collection.json
- 🗞 Description: Distribution of hapludalfs ofthe USDA soil great groups based on machine learning predictions from global compilation of soil profiles (>350,000 training points).
- 📝 Theme: Geology and Soils
- 📂 DOI: https://doi.org/10.5281/zenodo.3528062

### Potential distribution of biomes

- 🔗 URL: https://stac.openlandmap.org/biome.type_biome00k/collection.json
- 🗞 Description: Potential distribution of biomes (Potential Natural Vegetation) at 250 m spatial resolution based on the BIOME 6000 data set (8057 modern pollen-based site reconstructions). Predicted at 250 m using Ensemble Machine Learning and relief and climate variables representing the climate for the last 20+ years.
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.3526620

### Potential distribution of tropical evergreen broadleaf forest

- 🔗 URL: https://stac.openlandmap.org/biomes_biome6k.tropical.evergreen.broadleaf.forest/collection.json
- 🗞 Description: Probability and uncertainty maps showing the potential current natural vegetation (tropical evergreen broadleaf forest) on a global scale. Current (2022 - 2023) conditions are calculated on historical long term averages (1979 - 2013)
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.7822868

### Future potential distribution of tropical evergreen broadleaf forest (RCP 2.6)

- 🔗 URL: https://stac.openlandmap.org/biomes_biome6k.tropical.evergreen.broadleaf.forest.rcp26/collection.json
- 📰 Description: Probability and uncertainty maps showing the potential future natural vegetation (tropical evergreen broadleaf forest) on a global scale. Future projections (RCP 2.6) cover two different epochs: 2041 - 2060 and 2061 - 2080
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.7822868

### Future potential distribution of tropical evergreen broadleaf forest (RCP 4.5)

- 🔗 URL: https://stac.openlandmap.org/biomes_biome6k.tropical.evergreen.broadleaf.forest.rcp45/collection.json
- 📰 Description: Probability and uncertainty maps showing the potential future natural vegetation (tropical evergreen broadleaf forest) on a global scale. Future projections (RCP 4.5) cover two different epochs: 2041 - 2060 and 2061 - 2080
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.7822868

### Future potential distribution of tropical evergreen broadleaf forest (RCP 8.5)

- 🔗 URL: https://stac.openlandmap.org/biomes_biome6k.tropical.evergreen.broadleaf.forest.rcp85/collection.json
- 🗞 Description: Probability and uncertainty maps showing the potential future natural vegetation (tropical evergreen broadleaf forest) on a global scale. Future projections (RCP 8.5) cover two different epochs: 2041 - 2060 and 2061 - 2080
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.7822868

### Potential distribution of tropical savanna

- 🔗 URL: https://stac.openlandmap.org/biomes_biome6k.tropical.savanna/collection.json
- 🗞 Description: Probability and uncertainty maps showing the potential current natural vegetation (tropical savanna) on a global scale. Current (2022 - 2023) conditions are calculated on historical long term averages (1979 - 2013)
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.7822868

### Future potential distribution of tropical savanna (RCP 2.6)

- 🔗 URL: https://stac.openlandmap.org/biomes_biome6k.tropical.savanna.rcp26/collection.json
- 📰 Description: Probability and uncertainty maps showing the potential future natural vegetation (tropical savanna) on a global scale. Future projections (RCP 2.6) cover two different epochs: 2041 - 2060 and 2061 - 2080
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.7822868

### Future potential distribution of tropical savanna (RCP 4.5)

- 🔗 URL: https://stac.openlandmap.org/biomes_biome6k.tropical.savanna.rcp45/collection.json
- 🗞 Description: Probability and uncertainty maps showing the potential future natural vegetation (tropical savanna) on a global scale. Future projections (RCP 4.5) cover two different epochs: 2041 - 2060 and 2061 - 2080
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.7822868

### Future potential distribution of tropical savanna (RCP 8.5)

- 🔗 URL: https://stac.openlandmap.org/biomes_biome6k.tropical.savanna.rcp85/collection.json
- 📰 Description: Probability and uncertainty maps showing the potential future natural vegetation (tropical savanna) on a global scale. Future projections (RCP 8.5) cover two different epochs: 2041 - 2060 and 2061 - 2080
- 📝 Theme: Biodiversity and Nature Conservation
- 📂 DOI: https://doi.org/10.5281/zenodo.7822868

### GLC_FCS30D annual land land-cover dynamic monitoring product

- 🔗 URL: https://stac.openlandmap.org/lc_glc.fcs30d/collection.json
- 📰 Description: GLC_FCS30D is the first global fine land cover dynamic product at a 30-meter resolution that adopts continuous change detection. It utilizes a refined classification system containing 35 land-cover categories and covers the time span from 1985 to 2022. Before the year 2000, the update cycle was every 5 years, while after 2000, it is updated annually. In specific, it developed by combining the continuous change detection method, local adaptive updating models and the spatiotemporal optimization algorithm from dense time-series Landsat imagery, and was validated to achieve an overall accuracy of 80.88% (±0.27%) for the basic classification system 10 major land-cover types) and 73.24% (±0.30%) for the LCCS level-1 validation system (17 LCCS land-cover types).
- 📝 Theme: Land Cover and Land Use
- 📂 DOI: https://doi.org/10.5281/zenodo.8239305

### VIIRS annual nighttime lights

- 🔗 URL: https://stac.openlandmap.org/nightlights.average_viirs.v21/collection.json
- 📰 Description: The Annual Visible Night Light (VNL) V2 (VIIRS) images at 500-m spatial resolution for the period 2012 to 2021 (Elvidge et al., 2021) have been used to extrapolate the values backwards for years 2000–2011. This was done by fitting a logistic regression (per pixel) and then predicting the values for the previous years. Use with caution: extrapolation of values can lead to artifacts. For most of the land surface, however, it appears that the growth of night lights follows exponential growth function and hence nights in the past can be represented accurately by fitting decay / logistic regression function.
- 📝 Theme: Orthoimagery
- 📂 DOI: https://doi.org/10.5281/zenodo.8277198

### VIIRS long-term nighttime lights difference

- 🔗 URL: https://stac.openlandmap.org/nightlights.difference_viirs.v21/collection.json
- 🗞 Description: This dataset was derived by difference between average of the years 2020 / 2021 and years 2000 / 2021, showing an average rate of change for the 22 years period. Use with caution: extrapolation of values can lead to artifacts. For most of the land surface, however, it appears that the growth of night lights follows exponential growth function and hence nights in the past can be represented accurately by fitting decay / logistic regression function.
- 📝 Theme: Orthoimagery
- 📂 DOI: https://doi.org/10.5281/zenodo.8277198

