# urban_level

This repository shows the exploration fo the urban level in Italy. This is part of a larger project about covid in Italy, where tweets where analysed in the context of urban/rural divide. To do so, a  mapping of regions and their urban level was needed. However, upon looking at Eurostat data for urban level at LAU level (previously NUTS 5), and averaging those within regions, the initial result seemed nonsensical. I then decided to compute the average weighted by population to compute the urban level of each region. To do so, the population grid provided by eurostat was used, and geographically matched against the LAU boundaries. Then, the degree of urbanisation of LAUs was average within regions, weighted by the populations of the LAUs. This produced a map in accordance with expected results. 



## data sources
for the urban level: https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/population-distribution-demography/degurba
population grid: https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/population-distribution-demography/geostat
