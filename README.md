# PA-COVID #

**Contributors:** [mckinnon](https://opendna.com)  
**License:** GPLv2 or later  
**License URI:** [http://www.gnu.org/licenses/gpl-2.0.txt](http://www.gnu.org/licenses/gpl-2.0.txt)

 ## Description ##
 Pennsylvania COVID test results recorded daily by ZIP Code between Dec 10 2020 and July 25 2023

 ## Discussion ##
 From 2020 until July 25, 2023, the Pennsylvania Department of Health operated a COVID-19 Data dashboard<sup>1</sup> hosted on ESRI's ArcGIS service. As of February 2024, the dashboard is no longer public and the Internet Archive does not have a working copy. The project was described by the PA State Geospatial Coordinating Board in an undated COVID-19 Special Report<sup>2</sup> published on November 6, 2020. The weekly summaries of the data remain available from OpenData PA<sup>3</sup>, but this repository is believed to have the most granular data still public.

 Beginning Dec 10 2020, API calls against the ArcGIS service were run daily, after the afternoon updates by PA Health. For each ZIP code, records were pulled for COVID-19 test results reported Positive, Negative,a and Probable. The resulting HTML tables are published her by year. The records end with the termination of the service on July 25, 2023.

 ## License ##
 Original data is licensed Public Domain U.S. Government. GPLv2 has been applied as a best-fit of available options on GitHub.

 ## References ##
 1. Pennsylvania National Electronic Disease Surveillance System. (2023, July 25). COVID-19 Data for Pennsylvania Dashboard. https://experience.arcgis.com/experience/ed2def13f9b045eda9f7d22dbc9b500e Retrieved July 25 2023.
 2. PA State Geospatial Coordinating Board. (2020, November 6). COVID-19 Special Report. Retrieved from (https://www.oa.pa.gov/Programs/Information%20Technology/Documents/Geoboard-Report-COVID.pdf) on February 7 2024.
 3. Pennsylvania Department of Health. (2023, September 19). COVID-19 Aggregate Cases NO FURTHER UPDATES. Retrieved from (https://data.pa.gov/Covid-19/COVID-19-Aggregate-Cases-NO-FURTHER-UPDATES/j72v-r42c/about_data) on February 7 2024.

 ## Changelog ##

 ### 1.0.0 ###

 * Initial commit