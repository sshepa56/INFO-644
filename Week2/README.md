# Final project ideas: analyzing public health data sets

## Exploring social determinants of health by combining and visualizing data sets on Influenza hospitalizations, health insurance coverage, and leading cause of death
Using Python, I could combine NYC Open Data on influenza-related hospitalizations, leading cause of death, health insurance enrollment, and community health survey results to analyze examine potential patterns related to social determinants of health and regional patterns of influenza hospitalization outcomes. In addition to combining and analyzing correlations, I would visualize this data to communicate the story the data tells.

### Influenza hospitalizations [https://data.cityofnewyork.us/Health/Emergency-Department-Visits-and-Admissions-for-Inf/2nwg-uqyg/about_data]
Includes date, ZIP code, total ED visits, count of flu-like/pnuemonia ED visits, count of flu-like/pnuemonia hospital admissions. I am wondering about ways to look at admissions and health care enrollment by ZIP code.

### New York City Community Health Survey [https://data.cityofnewyork.us/Health/New-York-City-Community-Health-Survey/csut-3wpr/about_data]
The NYC community health insurance measures prevalence of several health access and health behavior factors (binary and quantitative). Columns include year, health insurance status, medical care accessed, primary care physician, flu shot status, self-reported health status, and colon cancer screening. Surveyed risk factors include smoking status, ≥ 12 oz sweet beverage, binge drinking, and obesity.

### Leading Cause of Death [https://data.cityofnewyork.us/Health/New-York-City-Leading-Causes-of-Death/jb7j-dtam/about_data]
Leading cause of death dataset records year, cause, sex, race, count of deaths due to specified cause of death, death rate by sex and race/ethnicity category, and age-adjusted death rate within the sex and race/ethinicty categories. I am interested in combining this data with acute viral illness admissions data and health insurance enrollment

### Health Systems with onsite enrollment assistance [https://data.cityofnewyork.us/Health/Equitable-Health-Systems-Health-Insurance-Enrollme/gfej-by6h/about_data]
The equitable health systems survey uses the most spatial data out of these sets by describing exact location, borough, community board district, taxlot council district, and census tract for each health care location included. Languages spoken and walk-in availability are also collected. This dataset describes health systems that can offer on-site SNAP and health insurance enrollment. It may be useful to compare the systems data with the community survey.
