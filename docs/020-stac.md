# OpenLandMap STAC 

::: {.rmdnote}
You are reading the work-in-progress OpenLandMap.org Open Land Data Services. This chapter is currently draft version, a peer-review publication is pending. You can find the polished first edition at <https://openlandmap.github.io/book/>.
:::



## Listing layers

Thanks to the STAC functionality and RStac package, it is possible to query directly 
which collections are available on the stac.OpenLandMap.org (Note: some layers that 
are available in STAC, might not be available in the front-end / web-GIS):


```r
library(rstac)
s_obj <- stac("https://s3.eu-central-1.wasabisys.com/stac/openlandmap/")
collections(s_obj)
#> [1m###RSTACQuery[22m
#> - [1murl:[22m https://s3.eu-central-1.wasabisys.com/stac/openlandmap/
#> - [1mparams:[22m
#> - [1mfield(s):[22m version, base_url, endpoint, params, verb, encode
```

For example, to list all layers with `collection_id` matching the land cover annual 
time-series from `lc_glc.fcs30d`, we can use e.g.:


## Spatial overlay

To overlay multiple new points with some COGs, we can create a new function:


```r
extract_xy = function(lon, lat, cogs, mc.cores=10){
  out = parallel::mclapply(paste0("/vsicurl/", cogs$filename.lst), function(i){terra::extract(terra::rast(i), 
        terra::vect(matrix(c(x, y), ncol = 2), crs="EPSG:4326"))}, mc.cores=mc.cores)
  out = dplyr::bind_cols(lapply(out, function(i){i[,2]}))
  names(out) = make.names(cogs$d.lst)
  return(out)
}
```

This only needs URL address of the COGs on some S3 storage and then longitude and 
latitude of the query points (in the WGS84 system). This is an example of query of 
all land cover classes from 1985 to 2022:


```r
#cogs
```


