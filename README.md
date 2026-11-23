
# Mapping Mortality in New York City

## Project Scopw

This project examines geographic patterns in mortality across New York City using 2023 death count data to explore post-pandemic mortality alongside health insurance enrollment, causes of death, and demographic factors. Using Python, Pandas, and Plotly, the project develops interactive visualizations to examine differences across NYC community districts and ZIP codes.

## Datasets

- **Deathratebycommunitydistrict.csv:** Mortality data by NYC community district, including total deaths and population.
- **Censuspopulationbycommunitydistrict2020.csv:** Population data used to calculate crude death rates.
- **EnrollmentbyZipcodeandWrittenLanguage.csv:** Health insurance enrollment counts by ZIP code, program type, and preferred written language.
- **nyc_districts.geojson:** Geographic boundaries for NYC community districts.
- **nyc-zip-code-tabulation-areas-polygons.geojson:** Geographic boundaries for NYC ZIP codes.

## Methodology
Data were cleaned, standardized, and analyzed using Pandas. Crude death rates  (*Crude Death Rate = (Total Deaths / Total Population) × 1,000*) were calculated for each community district and added to the death count data.
Mortality data were joined to community district boundaries, while insurance enrollment data were matched to ZIP code boundaries. Enrollment counts were aggregated from state data by ZIP code and program type.

## Visualizations
Interactive visualizations were developed using Plotly, including:
- **Mortality Choropleth Map:** Displays crude death rates per 1,000 residents across NYC community districts.
- **Insurance Enrollment Map:** Visualizes enrollment counts by ZIP code and program type.
- **Bar Charts:** Compare health insurance enrollment across program types and geographic areas.
- **Pie Charts:** Illustrate the distribution of insurance enrollment and cause of death by program type within selected ZIP codes available on the map.

# Tools Used
- Open Refine
- Python
- Pandas
- Plotly Express and Plotly Graph Objects
- GeoJSON
- Jupyter Notebook

## Limitations
A primary limitation is the difference in reporting years between datasets. The most recent decennial U.S. Census was conducted in 2020, while this project uses mortality counts from 2023 to examine post-pandemic patterns. Consequently, crude death rates calculated using 2020 population figures may not fully account for population changes between 2020 and 2023.
Crude death rates are not YET age-adjusted and may reflect differences in demographic composition across community districts. Insurance enrollment counts are not normalized by population and do not directly represent insurance coverage rates. Finally, community districts and ZIP codes represent different geographic units, limiting direct comparisons between mortality and enrollment data. These limitations should be considered when interpreting geographic patterns and potential relationships among mortality, insurance enrollment, causes of death, and demographic characteristics.
