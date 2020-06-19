# bayarea.map
public schools:
This Public Schools feature dataset is composed of all Public elementary and secondary education facilities in the United States as defined by the Common Core of Data(CCD, https://nces.ed.gov/ccd/ ), National Center for Education Statistics (NCES, https://nces.ed.gov ), US Department of Education for the 2015-2016 school year. This includes all Kindergarten through 12th grade schools as tracked by the Common Core of Data. Included in this dataset are military schools in US territories and referenced in the city field with an APO or FPO address. DOD schools represented in the NCES data that are outside of the United States or US territories have been omitted. This feature class contains all MEDS/MEDS+ as approved by NGA. Complete field and attribute information is available in the ”Entities and Attributes” metadata section. Geographical coverage is depicted in the thumbnail above and detailed in the Place Keyword section of the metadata. This release includes the addition of 1889 new records, modifications to the spatial location and/or attribution of 100385 records, and removal of 1985 records not present in the NCES CCD data. This feature class does not have a relationship class.


private schools:
This Private Schools feature dataset is composed of private elementary and secondary education facilities in the United States as defined by the Private School Survey (PSS, https://nces.ed.gov/surveys/pss/), National Center for Education Statistics (NCES, https://nces.ed.gov), US Department of Education for the 2015-2016 school year. This includes all prekindergarten through 12th grade schools as tracked by the PSS. This feature class contains all MEDS/MEDS+ as approved by NGA. Complete field and attribute information is available in the ”Entities and Attributes” metadata section. Geographical coverage is depicted in the thumbnail above and detailed in the Place Keyword section of the metadata. This release includes the addition of 3301 new records, modifications to the spatial location and/or attribution of 19127 records, and the retention of 8636 records from the previous PSS datasets that may or may not be closed (see STATUS field). The ADDRESS2 and DISTRICT_ID fields, previously populated with NOT AVAILABLE, have been removed. This feature class does not have a relationship class.


school districts:
School Districts are geographic entities and single purpose governmental units that operate schools and provide public educational services at the local level. The Census Bureau collects school district boundaries to develop annual estimates of children in poverty to help the U.S. Department of Education determine the annual allocation of Title I funding to states and school districts. NCES also uses the school district boundaries to develop a broad collection of district-level demographic estimates from the Census Bureau’s American Community Survey. The Census Bureau annually updates school district boundaries, names, local education agency codes, grade ranges, and school district levels based on information provided by state education officials.


median income, NSES: 
These layers show the socioeconomic status of each census tract. 
Data come from the US Census Bureau's 2011-2015 American Community Survey.

Neighborhood Socioeconomic Status, over and above individual socioeconomic status, is a predictor of many health outcomes.   

The Neighborhood Socioeconomic Status (NSES) Index is on a scale from 0 to 100 with 50 being the national average around 2010.  The Index incorporates the following indicators (fields in this layer's attribute table):
Median Household Income
Percent of households with income below the Federal Poverty Line
The educational attainment of adults (age 25+)
Unemployment Rate
Percent of households with children under the age of 18 that are "female-headed" (no male present)
NSES = log(median household income) + (-1.129 * (log(percent of female-headed households))) + (-1.104 * (log(unemployment rate))) + (-1.974 * (log(percent below poverty))) + .451*((high school grads)+(2*(bachelor's degree holders)))

