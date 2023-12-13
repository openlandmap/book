# Compendium of Global Gridded Environmental Data Sets

This is an open compendium of global gridded environmental datasets (bio-geophysical variables). Here you can 
you find systematic reviews of published data sets of interest to OpenLandMap.org 
with emphasis on publicly available data sets under open data license. These reviews are periodically 
maintained by the [www.OpenLandMap.org](https://openlandmap.org/) development team and 
collaborators. They are only meant to serve as general inventories of what is 
available, and not as an in-depth review article. To contribute to this portal, consider 
submitting new data by editing this Markdown document. Please check also the working 
version of the [OEMC global Land Use Land Cover Taxonomy Tables](https://docs.google.com/spreadsheets/d/1SX51OilNt-cUYpAa7t0LAvZRTzq3Sd4WJLnX6mWKfQk/edit?usp=sharing).

## Thematic data groups:

All layers are organized around the following themes 
(based on the [UN-GGIM The Global Fundamental Geospatial Data Themes](https://ggim.un.org/meetings/GGIM-committee/9th-Session/documents/Fundamental_Data_Publication.pdf)):

-  **Buildings and Settlements**: includes administrative and socio-economic data, natural hazards and similar,
-  **Elevation and Depth**: includes Digital Terrain Models and DEM-derived parameters, LiDAR point clouds, canopy heights, hydrological data derived from DTMs and similar,
-  **Geology and Soils**: includes geological, surface lithology and soil property and class maps,
-  **Land Cover and Land Use**: includes land cover / land use classes, land cover change and drivers of land use / land cover change, 
-  **Population Distribution**: includes population density and population variables, urbanization and lights at night images,
-  **Water**: includes surface and underground water resources and similar,
-  **Physical Infrastructure**: includes road and rail networks, dams, industrial facilities and similar,
-  **Climate**: includes long-term climatic images, climatic time-series data, future climate predictions and meteorological images,
-  **Biodiversity and Nature Conservation**: includes wildlife resources, protected areas, natural vegetation and biomes, ecoregions and biodiversity maps, 

## Other repositories of global (open) environmental layers

Sorted alphabetically:

* [Amazon AWS Open EO Data](https://registry.opendata.aws/tag/earth-observation/);
* [Atlas of the Biosphere portal](http://www.sage.wisc.edu/atlas/maps.php);
* [Copernicus Global Land Service](https://land.copernicus.eu/global/) — original global data sets (bio-geophysical products) produced by the Land Monitoring Core Service (LMCS) of Copernicus, the European flagship programme on Earth Observation;
* [Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets) — Google's repository of global and local data sets;
* [EarthEnv.org](http://earthenv.org/) — Global, remote-sensing supported environmental layers for assessing status and trends in biodiversity, ecosystems, and climate (hosted by Yale University / NASA and others);
* [Environmental Information Portal](http://earthtrends.wri.org/) of the World Resources Institute contains a number of global grids derived by the WRI and collaborators;
* [ESRI ArcGIS Living Atlas of the World](https://livingatlas.arcgis.com/en/home/);
* [Euro Data Cube Public Collections](https://collections.eurodatacube.com/) — a series of global data sets primarily based on the Copernicus programme / Sentinel satellites;
* [FAO's GeoNetwork](http://www.fao.org/geonetwork/srv/en/main.home) — serves a diversity of data produced by FAO run or supported projects at a diversity of scales;
* [Free GIS data compendium](http://freegisdata.rtwilson.com/) by R.T. Wilson;
* [GeoPortal.org](http://www.geoportal.org/) — The Global Earth Observation System of Systems (GEOSS) portal implemented and operated by the European Space Agency (typically only a catalog of data sets / no or limited data is hosted);
* [Global Land and Discovery group](https://glad.geog.umd.edu/) — University of Maryland Global Land and Discovery group (GLAD) group global data sets,
* [Natural Earth Data](http://www.naturalearthdata.com/downloads/) website compiled by Nathaniel Vaughn (KELSO) and volunteers;
* [Overture Maps](https://overturemaps.org/download/) by the Overture Maps Foundation serves some basic admin layers e.g. buildings, road networks, places etc all as open data.
* [SEDAC](https://sedac.ciesin.columbia.edu/data/sets/browse) — A Data Center in NASA's Earth Observing System Data and Information System (EOSDIS) — Hosted by CIESIN at Columbia University;
* [The awesome-gee-community-catalog](https://gee-community-catalog.org/) by Samapriya Roy et al.;
* [UNEP/GRID GEO DataPortal](http://geodata.grid.unep.ch/) and [UNEP/GRID-Arendal](http://maps.grida.no/region/global) — a large repository of global grids at various resolutions;

## Buildings and Settlements

### Administrative and socio economic data

Administrative data can be used to calculate proximity-based parameters and to 
orient the users geographically. One publicly accessible global administrative 
data database is the [GADM](http://gadm.org/) database of Global Administrative Areas 
GADM. It comprises borders of countries and lower level subdivisions such as provinces 
and counties (more than 100,000 areas). Lower level administrative boundaries can 
be obtained via the [FAO's GeoNetwork server](http://www.fao.org/geonetwork/srv/en/main.home).
Even more detailed is the [FAO GAUL: Global Administrative Unit Layers](https://data.apps.fao.org/map/catalog/static/search?keyword=HiH_boundaries) which is 
available for different periods and up to the 3rd admin level, so one can potentially 
also track changes in political units (the [table](/tabular/GAUL_g2015_2014_1_legend.csv) `GAUL_g2015_2014_1_legend.csv` 
contains an example of cca 3500 administrative units with codes). The [geoBoundaries](http://www.geoboundaries.org/) 
is a global Database of Political Administrative Boundaries and contains a snapshot 
of political and administrative boundaries since 2017.

An important global administrative dataset is the [World Vector Shoreline](https://shoreline.noaa.gov/data/datasheets/wvs.html) 
data set at scale 1:250,000 [@carlotto2017enhancing]. This can be, for example, 
used to derive the global distance from the sea coast line map and similar. 

The [Overture Maps foundation](https://overturemaps.org/download/) provides up-to-date (current) global vectors on 
Layers of interest include: admins, base, buildings, places etc. You can simply [download](https://github.com/OvertureMaps/data/) 
the data for are of interest, then convert to [PMTiles](https://msbarry.github.io/planetiler-overture-demo/) or similar, then add to back-end/front-end 
as clickable layer.

The [Socioeconomic Data and Applications Center (SEDAC)](https://sedac.ciesin.columbia.edu/data/sets/browse) a Data Center in NASA's Earth 
Observing System Data and Information System (EOSDIS) Hosted by CIESIN at Columbia University 
has number of global socio-economic data sets including on themes such as: Agriculture, Climate, Conservation, 
Governance, Hazards, Health, Infrastructure, Land Use, Marine and Coastal, Population, 
Poverty, Sustainability, Urban and Water.

## Elevation and Depth

### Digital Terrain Models

### Canopy height data

### Hydrological / hydrographic data

## Geology and Soils

### Geology and lithology

### Earthquakes / natural hazards

### Soils

## Land Cover and Land Use

### Land cover 

Land cover maps show distribution of above-surface cover in general categories and 
are used primarily for spatial planning and modeling. Ground truth observations of 
land cover can be obtained from multiple sources e.g. [geo-wiki.org](http://geo-wiki.org/) 
project [@Fritz2017], 
[FROM-GLC](http://data.ess.tsinghua.edu.cn/) [@GONG2019370]; 
the most comprehensive recent global training data sets for land cover mapping to 
date (cca 2M training points covering from years 1984 to 2020) is provided by the 
[Global Land Cover Estimation (GLanCE) project](https://sites.bu.edu/measures/) project [@Stanimirova2023].

Land cover maps are commonly derived using semi-automated methods and remote sensing 
images as the main inputs. Global land cover / land cover change maps are today primarily derived from the Sentinel-2 
and Landsat imagery. For example, the [GlobalForestWatch.org](http://globalforestwatch.org/) 
imagery showing deforestation/reforestation were derived from the 30 m resolution Landsat 
images [@hansen2013high]. The global 
Analysis-Ready Landsat mosaics ([Landsat-ARD](https://glad.geog.umd.edu/ard/glad-landsat-ard)) 
are available for download as harmonized scenes from the University of Maryland GLAD ([Global Land and Discovery group](https://glad.geog.umd.edu/)) [@rs12030426], 
but these datasets are significant in size and hence require significant processing facilities. 

Current publicly available global land cover, land use maps include [@Liu2021]:

* **[GLASS-GLC](https://doi.org/10.1594/PANGAEA.913496)** is global land cover time-series 1982 to 2015 at 5-km resolution derived directly in Google Earth Engine [@Liu2020ESSD].
* **[MCD12Q1 Land Cover Type Yearly L3 Global](https://lpdaac.usgs.gov/products/mcd12q1v061/)** product available in resolution from 500 m. MODIS Land cover maps (17 land cover classes based on the [International Geosphere Biosphere Programme](http://www.igbp.net/) IGBP classification system) is a temporal dataset so that one can also derive various change indices and quantify the land cover dynamics.
* **[ESA CCI Land cover](http://www.esa-landcover-cci.org/)** is a global land cover time series from 1992 to 2020+ derived at 300-m spatial resolution from MERIS, SPOT and PROBA-V imagery. Maps can be accessed through a [viewer](http://maps.elie.ucl.ac.be/CCI/viewer/) and downloaded from the ESA website or from zenodo.org.
* **[Copernicus Global Land Cover](https://land.copernicus.eu/global/products/lc)** products at 100-m for years 2015, 2016, 2017 and 2018 and based on the PROBA-V imagery [@rs12061044]. The maps which can be downloaded directly from [zenodo.org](https://zenodo.org/communities/copernicus-land-cover/). This maps contain also predicted fractions for the main land cover classes (per pixel).
* **[GLAD Global Land Cover and Land Use Change 2000–2020 (GLCLUC2020)](https://glad.umd.edu/dataset/GLCLUC2020)** provides estimate of the land cover for the last 20+ years but also quantifies changes in forest extent and height, cropland, built-up lands, surface water, and perennial snow and ice extent [@Potapov2022].
* **[GLC FCS30D](https://zenodo.org/doi/10.5281/zenodo.8239304)** is a global 30-m annual land-cover time-series data set with 17-class system for the period 1982–2021 [@Zhang2021].

A detailed Water mask of the world is available also from the [Global Surface Water Explorer](https://global-surface-water.appspot.com/) hosted by European Commission JRC 
[@Pekel2016]. A Landsat-based water 
dynamics assessment at 30-m is also provided by @pickens2020mapping. 

Due to the availability of the Sentinel-2 10-m resolution data, several land cover 
products are now available at very high resolution (but then only covering recent 3–5 years). These includes:

* **[Google Dynamic World](https://dynamicworld.app/)** at 10-m, limited to 9 classes but constantly updated [@Brown2022];
* **[ESA World Cover](https://esa-worldcover.org/en)** at 10-m based on Sentinel-1 and Sentinel-2 data for 2020 and 2021 available from [Zenodo](https://doi.org/10.5281/zenodo.7254221);  
* **[Global canopy top height map for the year 2020](https://langnico.github.io/globalcanopyheight/)** at 10-m [@lang2023high];

Several initiatives aim at integrating multiple land cover products [@rs8121036] 
and/or running land cover classification by fusing multisource EO data [@Song2017, @Liu2021]. 

### Forest resources

FAO periodically (every 5 years) organizes the so called [Forest Resources Assessment](https://www.fao.org/forest-resources-assessment/en/) (FRA) — 
an international compilation of forest resource assessment (forest maps, health 
and vitality status, forest functions and policies connected with forest management). 
This assessment typically results in a comprehensive report that includes both graphical 
and [tabular data](https://fra-data.fao.org/); gridded global FRA maps are typically not available. 

The Land Processes Distributed Active Archive Center (LP DAAC) archives and distributes 
[Global Forest Cover Change (GFCC) data product](https://lpdaac.usgs.gov/products/gfcc30fccv001/) at 30-m resolution. 
Japan Aerospace Exploration Agency (JAXA) has also released in 2014 a global 
[25-m resolution PALSAR mosaic and forest/non-forest map (2007–2010 and 2015–2021)](https://www.eorc.jaxa.jp/ALOS/en/dataset/fnf_e.htm). This data is freely available for download via the [JAXA pages](https://www.eorc.jaxa.jp/ALOS/en/palsar_fnf/data/).

Forest resources and canopy height have been mapped by the GLAD group from the Maryland university [@POTAPOV2021112165]
The data is publicly available under open data license from https://glad.umd.edu/dataset.

### Land use change

## Population Distribution

### Population density maps

The most important global socio-economic data layers are the population density 
maps and attached socio-economic variables. The [Socioeconomic Data and Applications Center](https://sedac.ciesin.columbia.edu/) (SEDAC) distributes The [Global Population Density Grid Time Series Estimates](https://doi.org/10.7927/H47M05W2) (1970-2000), 
Global Rural-Urban Mapping Project, Version 1 ([GRUMPv1](https://doi.org/10.7927/np6p-qe61)) and Gridded Population 
of the World, Version 4 ([GPWv4](https://doi.org/10.7927/H49C6VHW)) all at resolution of up to 1 km. These are the currently most 
detailed gridded dataset with consistent population density and structure; for modeling future, 
a [Global 1-km Downscaled Population Base Year and Projection Grids Based on the SSPs](https://doi.org/10.7927/q7z9-9r69) (1990-2100) [@gao2020global] is also available. It consists of global urban, rural, and total population 
for the base year 2000, population projections at ten-year intervals for 2010-2100 
at a resolution of 1-km, and was developed for the purpose of the IPCC climate modeling framework.

Joint Research Centre (JRC) of the European Commission has produced a global 100-m 
spatial resolution product called **[Global Human Settlement (GHS) population grid multitemporal (1975-2030) layer](https://doi.org/10.2905/2FF68A52-5B5B-4A22-8F40-C41DA8332CFE)** 
[@schiavina2022ghsl]. This can be considered the most detailed global population density product to date 
and is also [available via OpenLandMap.org](https://stac.openlandmap.org/pop.count_ghs.jrc/collection.json).

### Lights at night images

he lights at night map contains the lights from cities, towns, and other sites 
with persistent lighting, including gas flares. Images of lights at night have shown 
to be highly correlated with industrial activity and Gross Domestic Product [@doll2006mapping]. 
A time-series of (1 km resolution) annual global night light images (1992–2013) is available via the NOAA's 
National Geophysical Data Center [the Version 4 DMSP-OLS Nighttime Lights Time Series](https://ngdc.noaa.gov/eog/dmsp/downloadV4composites.html). 
The [harmonized nighttime light (NTL) time-series composites for 1992–2020](https://doi.org/10.6084/m9.figshare.16602224.v1) are 
available at 1-km resolution [@zhao2022global].

Currently the most detailed global Lights at night images at 500-m spatial resolution are 
the global VIIRS nighttime lights ([Annual VNL V2](https://eogdata.mines.edu/products/vnl/#annual_v2)) covering 2012–2020 [@elvidge2021annual]. 
This contain average, average-masked, mean, minimum and maximum values of nighttime lights.
The [lights at night images on OpenLandMap.org](https://stac.openlandmap.org/nightlights.average_viirs.v21/collection.json?.language=en) are based on extrapolated values so that they cover 2000–2022 
and are hence compatible with other global land products.

## Water

## Physical Infrastructure

### Urbanization

To quantify urbanization one can either use population density maps, lights at night 
images and/or data on buildings. Partners in the [GLOBIO consortium](https://www.globio.info/resources) created a World Map 
of **Human Impacts on the Biosphere** for various time periods. This is basically 
a map showing a current status of the roads, railways and settlement density. 
Human impact maps can be also browsed via the [UNEP Grid Arendal](http://grida.no/). 
@weiss2018global and @weiss_global_2020 have produced [a global map of accessibility and optimal travel time to healthcare](https://data.malariaatlas.org/maps). 

The International Biosphere-Geosphere Programme, the Stockholm Environment Institute, 
the Stockholm Resilience Center, the CSIRO in Australia and the International Human 
Dimensions Programme on Global Environmental Change are producing an outreach project 
on the Anthropocene and planetary boundaries named ["Globaia"](https://globaia.org/). 

### Intact forest landscapes

A comprehensive global assessment of the human impacts to marine ecosystems can 
be followed via the work of the [National Center for Ecological Analysis and Synthesis](http://www.nceas.ucsb.edu/) in Santa Barbara. 
This group have produced [a Global Map of Human Impacts to Marine Ecosystems](http://www.nceas.ucsb.edu/globalmarine) by 
using a number of connected input GIS layers [@Halpern2008], which are available 
for [download](https://doi.org/10.5063/F1S180FS). Distribution of global airports 
and flight routes can be freely accessed from the [openflights.org](https://github.com/jpatokal/openflights). 
Chris Harrison produced the [world map](http://www.chrisharrison.net/projects/InternetMap/) of 
internet connectivity and traffic.

## Climate

## Biodiversity and Nature Conservation

### World ecosystems / biomes / ecoregions

### Species distribution maps

### Protected areas

