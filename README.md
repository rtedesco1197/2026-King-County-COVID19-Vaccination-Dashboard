Project contains a PowerBI dashboard for COVID-19 Vaccination Rates broken out by social determinants (King county region, age group, race/ethnicity).

Data is available from https://kingcounty.gov/en/dept/dph/health-safety/disease-illness/covid-19/data
King County shape map is available from https://gis-kingcounty.opendata.arcgis.com/datasets/public-health-regions/explore?location=47.430916%2C-121.802557%2C10

Process for the project is as follows:
1. Gather required data files (2026-King-County-COVID19-Vaccination-Dashboard/Data)
2. Transform data files in Python, wide to long transpose (2026-King-County-COVID19-Vaccination-Dashboard/Python)
3. Create a simple year CSV/XLSX file for the PBI data model (2026-King-County-COVID19-Vaccination-Dashboard/PBI)
4. Create the data model in PBI (don't forget the shape map) and publish to blog using Fabric
