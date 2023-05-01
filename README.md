##  Differential Spatial-Social Accessibility to Mental Health Care and Suicide

Source code for the 2023 Tadmon and Bearman PNAS article *"[Differential Spatial-Social Accessibility to Mental Health Care and Suicide](https://www.pnas.org/doi/10.1073/pnas.2301304120)"*. 

To run, decompress `data.zip` in working directory and run the following code (in order):
* `1 matrix construction.R` (R)
* `2 calculate 3sfca.ipynb` (Python)
* `3 accessibility score calculator.R` (R)
* `4 suicide.R` (R)

Data sources used and their availability:
1. 5-year ACS data for 2019 (through Census: https://data.census.gov/)
2. Wisconsin Neighborhood Atlas ADI data (included)
3. Social Capital Project data (included)
4. RUCA rurality data (included)
5. County and Census tract shapefiles (counties included; tracts through NHGIS: https://www.nhgis.org/data-availability#gis-files)
6. Travel cost matrices (through PySal: https://pysal.org/)
7. Gun and liquor business data from Historic Business Database (proprietary, through Data Axle: https://www.data-axle.com/our-data/business-data/)
8. County-level death data (restricted, through CDC: https://www.cdc.gov/nchs/nvss/nvss-restricted-data.htm)
9. Provider location data (proprietary, through state licensing boards, AMA and AOA).

See further detail in *Materials and Methods* and in *SI Appendix 6*. For data sources 6-9 above, placeholders demonstrating needed file structure for replication are attached. 