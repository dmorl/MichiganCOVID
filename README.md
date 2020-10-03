# Coronavirus Michigan COVID-19 Overview Tracking
Four spreadsheets aggregating COVID probable and confirmed cases counts and demographics released daily by the Michigan Department of Health &amp; Human Services

-------------------------------------------

**Author:** Daria Orlowska <br />
**Contact:** daria.orlowska@wmich.edu <br />
**Last Updated:** 2020-10-03 18:22 <br />

-------------------------------------------

## Spreadsheet Overviews

### MichiganOverview_Cases.csv

**Source:** Data is found under the Cumulative Data link of Michigan's Coronavirus webpage, https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html (obsolete) and https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html (active) <br />
**Description:** A spreadsheet converting tabular data of confirmed COVID-19 cases in Michigan released by the Michigan Department of Health & Human Services. Confirmed cases only include individuals who have had a positive diagnostic laboratory test for COVID-19 <br />
**Date range:** 2020-03-10 through 2020-10-03 <br />
**Missing dates:** 2020-03-20, 2020-08-21, 2020-09-06 <br />

**Author notes:** This spreadsheet combines multiple tables with counts and demographics about confirmed COVID-19 cases in Michigan for ease of use. Variables are parsed into sections providing additional information about each table <br />
As of 2020-06-05, Michigan.gov has moved over to the Microsoft Power BI data dashboard to display statistics. As a result, archiving the webpage is no longer effective. Some table names have changed, so SECTIONS now include a TableDescription that describes variable location pre-dashboard, and DashDescription, that describes variable location post-dashboard relocation. As a result of the move, some variables are no longer reported while others have been added. Notably, many variables are now being reported as raw numbers instead of percentages <br />
As of 2020-09-06, data on cases, deaths and testing will be reported Monday – Saturday due to the erratic nature of weekend data.
---

### MichiganOverview_Deceased.csv

**Source:** Data is found under the Cumulative Data link of Michigan's Coronavirus webpage, https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html (obsolete) and https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html (active) <br />
**Description:** A spreadsheet converting tabular data of confirmed COVID-19 deceased cases in Michigan released by the Michigan Department of Health & Human Services. Confirmed deaths include individuals who meet one or more of the following conditions: 1) Have been identified as a confirmed case and classified as deceased as a result of a case investigation in the Michigan Disease Surveillance System (MDSS). MDSS is the database used by state and local health department to monitor reportable diseases like COVID-19; 2) have been identified as a confirmed case in MDSS had have a death certificate with COVID-19 listed as a cause of death; 3) have been identified as a confirmed case in MDSS and die within 30 days of onset of COVID-19 infection and have a death certificate which classifies their manner death as 'natural' <br />
**Date range:** 2020-03-10 through 2020-10-03 <br />
**Missing dates:** 2020-03-20, 2020-08-21, 2020-09-06 <br />

**Author notes:** This spreadsheet combines multiple tables with counts and demographics about confirmed COVID-19 deceased cases in Michigan for ease of use. Variables are parsed into sections providing additional information about each table <br />
As of 2020-06-05, Michigan.gov has moved over to the Microsoft Power BI data dashboard to display statistics. As a result, archiving the webpage is no longer effective. Some table names have changed, so SECTIONS now include a TableDescription that describes variable location pre-dashboard, and DashDescription, that describes variable location post-dashboard relocation. As a result of the move, some variables are no longer reported while others have been added. Notably, many variables are now being reported as raw numbers instead of percentages <br />
As of 2020-09-06, data on cases, deaths and testing will be reported Monday – Saturday due to the erratic nature of weekend data.

---

### MichiganOverview_ProbableCases.csv

**Source:** Data is found under the Cumulative Data link of Michigan's Coronavirus webpage https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
**Description:** A spreadsheet converting dashboard data of COVID-19 probable cases in Michigan released by the Michigan Department of Health & Human Services. Probable cases include individuals who have symptoms consistent with COVID-19 and an epidemiologic link to a confirmed case or a positive serology (antibody) test, but do not have a positive diagnostic laboratory test for COVID-19 and individuals with a positive serology (antibody) test for COVID-19 and an epidemiologic link to a confirmed case. The number of probable cases can change daily based on information obtained through the health department investigation. Probable cases can be re-classified as a confirmed case or determined to not be a case <br />
**Date range:** 2020-03-01 through 2020-10-03 <br />
**Missing dates:** 2020-08-21, 2020-09-06 <br />

**Author notes:** As of 2020-06-05, Michigan.gov has moved over to the Microsoft Power BI data dashboard and began reporting probable COVID cases. However, the Author did not begin collecting demographic information on probable cases until 2020-06-07 <br />
Probable cases can increase as more unconfirmed COVID-19 cases are identified, and decrease as these probable cases are confirmed and added to the official COVID-19 case count, or disconfirmed as cases and removed from the spreadsheet <br />

On 2020-06-13, MDHHS released the downloadable file "Confirmed and Probable Cases by County by Date" (subsequently "Cases by County by Date") ranging from March 2020 onwards. Therefore, numbers between 2020-03-01 and 2020-06-04 are taken from a different source than the dashboard and may result in some discrepancies <br />
As of 2020-09-06, data on cases, deaths and testing will be reported Monday – Saturday due to the erratic nature of weekend data.

---

### MichiganOverview__ProbableDeceased.csv

**Source:** Data is found under the Cumulative Data link of Michigan's Coronavirus webpage https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
**Description:** A spreadsheet converting dashboard data of probable deceased COVID-19 cases in Michigan released by the Michigan Department of Health & Human Services. Probable deaths include individuals who have COVID indicated as a cause of death on their death certificate but have not had a positive diagnostic laboratory test <br />
**Date range:** 2020-03-01 through 2020-10-03 <br />
**Missing dates:** 2020-08-21, 2020-09-06 <br />

**Author notes:** As of 2020-06-05, Michigan.gov has moved over to the Microsoft Power BI data dashboard and began reporting probable COVID cases. However, the Author did not begin collecting demographic information on probable cases until 2020-06-07 <br />
Probable deceased cases can increase as more unconfirmed COVID-19 cases are identified, and decrease as these probable deceased cases are confirmed and added to the official COVID-19 deceased count, or disconfirmed as deceased cases and removed from the spreadsheet <br />

On 2020-06-13, MDHHS released the downloadable file "Confirmed and Probable Cases by County by Date" (subsequently "Cases by County by Date") ranging from March 2020 onwards. Therefore, numbers between 2020-03-01 and 2020-06-04 are taken from a different source than the dashboard and may result in some discrepancies <br />
As of 2020-09-06, data on cases, deaths and testing will be reported Monday – Saturday due to the erratic nature of weekend data.

-------------------------------------------

## Spreadsheet Variables

### MichiganOverview_Cases.csv

CheckedEST
* Column: A
* Description: Data and time (YYYY-MM-DD HH:MM) in Eastern Standard Time (EST) when Author collected data
* Values: Date
* Missing values reason: Unable to get link from the Internet Archive due to an error <br />

Link
* Column: B
* Description: Link to archived page in the Web Archive (WaybackMachine)
* Values: String
* Missing values reason: This value should never be missing <br />
Note: Sometimes pages archived in the Web Archive did not register, in which case the link does not work as expected. Internet Archive doesn't support dashboard archiving, so no data within the Microsoft Power BI dashboard is captured (starting from 2020-06-05). Contact Author for pdf versions of the dashboard to view all captured data pages. 

Date
* Column: C
* Description: Date of contained information, in YYYY-MM-DD format
* Values: Date
* Missing values reason: This value should never be missing <br />

- SECTION CountyOverview - <br />

Column range: D through CO <br />
TableDescription: Information from aggregated table "Confirmed COVID-19 Cases by Jurisdiction", column "Confirmed Cases", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
DashDescription: Information from the tab "Current Status", in the subsection "Covid-19 Cases and Deaths by County" under the section "View Table", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-03-10 <br />
Author notes: The off-shoot cumulative data page (https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html) did not exist until 2020-03-17. Information between 2020-03-10 and 2020-03-15 was filled in using the daily statistics from the main page https://www.michigan.gov/coronavirus <br />
On 2020-03-21, reporting practices changed from reporting yesterday's results to reporting same day results (as of 10am). Therefore, data from 2020-03-20 is missing from the dataset <br />

Columns D through CH
* Description: Names of Michigan counties reporting confirmed COVID cases, in the format C_<County>
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed cases at the time of the report <br />
Note: Originally, counties were only added to spreadsheet at the time of a positive case, but to avoid updating column references in the documentation, all 83 Michigan counties have been added. County is based on the county of residence

C_MDOC
* Column: CI
* Description: The number of confirmed COVID cases originating in the Michigan Department of Corrections (MDOC) in Michigan
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed cases at the time of the report <br />
Note: On 2020-03-26, "Other" was added to the count to represent "D_MDOC" as a seperate jurisdiction, and resulted in case reclassification. The category "Other" was discontinued on 2020-04-10, and split into "D_MDOC" and "D_FCI"

C_FCI
* Column: CJ
* Description: The number of confirmed COVID cases originating in the Federal Corrections Institution (FCI) in Michigan 
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed cases at the time of the report <br />
Note: The variable "D_FCI" was first introduced on 2020-04-10; see "D_MDOC" Note

C_OutState
* Column: CK
* Description: The number of confirmed COVID cases from out of state in Michigan 
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed cases at the time of the report <br />
Note: The variable "D_OutState" was first introduced on 2020-03-20. This variable fluctuates as cases are reassigned to their home states

C_NR
* Column: CL
* Description: The number of confirmed COVID cases with unknown origin in Michigan 
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed cases at the time of the report <br />
Note: The variable "D_NR" was first introduced on 2020-03-19. This variable fluctuates as more information is obtained and cases are reassigned to a specific Michigan county or to a county out of state

C_TOTAL
* Column: CM
* Description: The derived number of total daily confirmed COVID cases in Michigan. Obtained by horizontally summing of all county and NR cases in the same row 
* Values: Integer
* Missing values reason: This value should never be missing

C_Detroit
* Column: CN
* Description: The number of confirmed COVID cases occuring in Detroit
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed cases at the time of the report <br />
Note: City of Detroit and Wayne County are reported separately. Since Detroit is in Wayne County, the Author has combined both of these numbers in the Wayne county count and included the Detroit-only count after the TOTAL column, for reference.

C_Probable
* Column: CO
* Description: Probable but unconfirmed (by testing) total COVID cases in Michigan. Obtained from the tab "Current Status", in the subsection "Current Totals" 
* Values: Integer
* Missing values reason: This value may be missing if not applicable or not provided <br />
Note: First introduced 2020-06-05. Probable cases include individuals who have symptoms consistent with COVID-19 and an epidemiologic link to a confirmed case or a positive serology (antibody) test, but do not have a positive diagnostic laboratory test for COVID-19 and individuals with a positive serology (antibody) test for COVID-19 and an epidemiologic link to a confirmed case. The number of probable cases can change daily based on information obtained through the health department investigation. Probable cases can be re-classified as a confirmed case or determined to not be a case

C_Notes
* Column: CP
* Description: Additional information posted on the website, or notes by the Author to indicate discrepancies 
* Values: String
* Missing values reason: No notes before 2020-03-16 <br />

- SECTION CaseSex - <br />

Column range: CQ through CS <br />
TableDescription: Information from aggregated table "Cases by Sex", column "Percentage of Overall Cases by Sex", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
   TableWebsite note: Totals may not add to 100% due to rounding <br />
DashDescription: Information from the tab "Demographics", in the subsection "Cases by Sex" using the selection "Cases --> Confirmed", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
   DashWebsite note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />
Date range: Contains ongoing data after 2020-03-16 <br />
Author note: Some percentages are recorded as "<1%", which may need to be transformed before analysis. Post migration to the dashboard on 2020-06-05, values are now presented as raw data instead of percentages <br />

C_Male
* Column: CQ
* Description: Confirmed male COVID cases across Michigan
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_Female
* Column: CR
* Description: Confirmed female COVID cases across Michigan
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_SexNR
* Column: CS
* Description: Confirmed COVID cases across Michigan where sex was not reported
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided <br />

- SECTION CaseAge - <br />

Column range: CT through DB <br />
TableDescription: Information from aggregated table "Cases by Age", column "Percentage of Overall Cases by Age", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
   TableWebsite note: Totals may not add to 100% due to rounding <br />
DashDescription: Information from the tab "Demographics", in the subsection "Cases by Age Group" using the selection "Cases --> Confirmed", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
   DashWebsite note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />
Date range: Contains ongoing data after 2020-03-16 <br />
Author note: Some percentages are recorded as "<1%", which may need to be transformed before analysis. Post migration to the dashboard on 2020-06-05, values are now presented as raw data instead of percentages <br />

C_0_19
* Column: CT
* Description: Confirmed COVID cases across Michigan between the ages of 0 to 19
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided  <br />
Note: As of 2020-08-02, this category was split into 2 categories: ages 0 to 9 and ages 10 to 19. In order to preserve ability to compare across dates, these two categories are now summed in the dataset

C_20_29
* Column: CU
* Description: Confirmed COVID cases across Michigan between the ages of 20 to 29
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_30_39
* Column: CV
* Description: COnfirmed COVID cases across Michigan between the ages of 30 to 39
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_40_49
* Column: CW
* Description: Confirmed COVID cases across Michigan between the ages of 40 to 49
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_50_59
* Column: CX
* Description: Confirmed COVID cases across Michigan between the ages of 50 to 59
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_60_69
* Column: CY
* Description: Confirmed COVID cases across Michigan between the ages of 60 to 69
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_70_79
* Column: CZ
* Description: Confirmed COVID cases across Michigan between the ages of 70 to 79
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_80_plus
* Column: DA
* Description: Confirmed COVID cases across Michigan between the ages of 80 to 89
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_AgeNR
* Column: DB
* Description: Confirmed COVID cases across Michigan with unknown/not reported age
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided <br />

- SECTION CaseRace - <br />

Column range: DC through DI <br />
TableDescription: Information from aggregated table "Cases by Race", column "Percentage of Overall Cases by Race", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
   TableWebsite note: Totals may not add to 100% due to rounding <br />
DashDescription: Information from the tab "Demographics", in the subsection "Cases by Race" using the selection "Cases --> Confirmed", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
   DashWebsite note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />
Date range: Contains ongoing data after 2020-04-02 <br />
Author note: Some percentages are recorded as "<1%", which may need to be transformed before analysis. Post migration to the dashboard on 2020-06-05, values are now presented as raw data instead of percentages <br />

C_Native
* Column: DC
* Description: Confirmed COVID cases across Michigan identifying as American Indian or Alaska Native
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_Asian
* Column: DD
* Description: Confirmed COVID cases across Michigan identifying as Asian/Pacific Islander
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_Black
* Column: DE
* Description: Confirmed COVID cases across Michigan identifying as Black or African American
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_White
* Column: DF
* Description: Confirmed COVID cases across Michigan identifying as Caucasian
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_Many
* Column: DG
* Description: Confirmed COVID cases across Michigan identiyfing as Multiple Races
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_Other
* Column: DH
* Description: Confirmed COVID cases across Michigan identifying as Other
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

C_RaceNR
* Column: DI
* Description: Confirmed COVID cases across Michigan of unknown/not reported race
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided <br />

- SECTION CaseEthnicityHispanic - <br />

Column range: DJ through DL <br />
Description: Information from aggregated tables "Cases by Hispanic/Latino Ethnicity", column "Percentage of Overall Cases by Ethnicity", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
Date range: Contains ongoing data after 2020-04-02 <br />
Website note: Totals may not add to 100% due to rounding <br />

C_Hispanic
* Column: DJ
* Description: Confirmed COVID cases across Michigan identifying as Hispanic/Latino
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

C_NonHispanic
* Column: DK
* Description: Confirmed COVID cases across Michigan identifying as Non- Hispanic/Latino
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

C_HispanicNR
* Column: DL
* Description: Confirmed COVID cases across Michigan with unknown Hispanic ethnic affiliation
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided <br />

- SECTION CaseEthnicityArab - <br />

Column range: DM through DO <br />
Description: Information from aggregated tables "Cases by Arab Ethnicity", column "Percentage of Overall Cases by Ethnicity", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
Date range: Contains ongoing data after 2020-04-17 <br />
Website note: Totals may not add to 100% due to rounding <br />

C_Arab
* Column: DM
* Description: Confirmed COVID cases across Michigan identifying as Arab
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

C_NonArab
* Column: DN
* Description: Confirmed COVID cases across Michigan identiyfing as Non-Arab
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

C_ArabNR
* Column: DO
* Description: Confirmed COVID cases across Michigan with unknown Arab ethnic affiliation
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

---

### MichiganOverview_Deceased.csv

CheckedEST
* Column: A
* Description: Data and time (YYYY-MM-DD HH:MM) in Eastern Standard Time (EST) when Author collected data
* Missing values reason: Unable to get link from the Internet Archive due to an error <br />

Link
* Column: B
* Description: Link to archived page in the Web Archive (WaybackMachine)
* Values: String
* Missing values reason: This value should never be missing <br />
Note: Sometimes pages archived in the Web Archive did not register, in which case the link does not work as expected. Internet Archive doesn't support dashboard archiving, so no data within the Microsoft Power BI dashboard is captured (starting from 2020-06-05). Contact Author for pdf versions of the dashboard to view all captured data pages.

Date
* Column: C
* Description: Date of contained information, in YYYY-MM-DD format
* Values: Date
* Missing values reason: This value should never be missing <br />

- SECTION DeceasedOverview - <br />

Column range: D through CP <br />
TableDescription: Information from aggregated table "Confirmed COVID-19 Cases by Jurisdiction", column "Reported Deaths" <br />
DashDescription: Information from the tab "Current Status", in the subsection "Covid-19 Cases and Deaths by County" under the section "View Table", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-03-18 <br />
Author notes: On 2020-03-21, reporting practices changed from reporting yesterday's results to reporting same day results (as of 10am). Therefore, data from 2020-03-20 is missing from the dataset <br />

Columns D through CH
* Description: Names of Michigan counties reporting confirmed deceased COVID cases, using the format D_<County>
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed deceased cases at the time of the report <br />
Note: Originally, counties were only added to spreadsheet at the time of a death, but to avoid updating column references in the documentation, all 83 Michigan counties have been added. County is based on the county of residence

D_MDOC
* Column: CI
* Description: The number of confirmed deceased COVID cases originating in the Michigan Department of Corrections (MDOC) in Michigan
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed deceased cases at the time of the report <br />
Note: The variable "D_MDOC" was first introduced on 2020-04-03

D_FCI
* Column: CJ
* Description: The number of confirmed deceased COVID cases originating in the Federal Corrections Institution (FCI) in Michigan 
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed deceased cases at the time of the report <br />
Note: The variable "D_FCI" was first introduced on 2020-04-25

D_OutState
* Column: CK
* Description: The number of confirmed deceased COVID cases from out of state in Michigan 
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed deceased cases at the time of the report <br />
Note: The variable "D_OutState" was first introduced on 2020-04-01. This variable fluctuates as cases are reassigned to their home states

D_NR
* Column: CL
* Description: The number of confirmed decease COVID cases with unknown origin in Michigan 
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed deceased cases at the time of the report <br />
Note: The variable "D_NR" was first introduced on 2020-04-01. This variable fluctuates as more information is obtained and cases are reassigned to a specific Michigan county or to a county out of state

D_TOTAL
* Column: CM
* Description: The derived number of total confirmed COVID deceased cases in Michigan. Obtained by horizontally summing of all county, MDOC, FCI, out of state, and NR cases in the same row 
* Values: Integer
* Missing values reason: This value should never be missing

D_Detroit
* Column: CN
* Description: The number of confirmed COVID deceased cases occuring in Detroit
* Values: Integer
* Missing values reason: Blank cells indicate lack of confirmed deceased cases at the time of the report <br />
Note: City of Detroit and Wayne County are reported separately. Since Detroit is in Wayne County, the Author has combined both of these numbers in the Wayne county count and included the Detroit-only count after the TOTAL column, for reference.

D_Probable
* Column: CO
* Description: Probable but unconfirmed total deceased COVID cases in Michigan. Obtained from the tab "Current Status", in the subsection "Current Totals"
* Values: Integer
* Missing values reason: Value not provided <br />
Note: First introduced 2020-06-05. Probable deaths include individuals who have COVID indicated as a cause of death on their death certificate but have not had a positive diagnostic laboratory test

D_Notes
* Column: CP
* Description: Additional information about the "Confirmed COVID-19 Cases by Jurisdiction" table posted on the website, or notes by the Author to indicate discrepancies
* Values: String
* Missing values reason: No notes before 2020-03-19 <br />

- SECTION DeceasedSex - <br />

Column range: CQ through CS <br />
TableDescription: Information from aggregated table "Cases by Sex", column "Percentage of Deceased Cases by Sex", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
   TableWebsite note: Totals may not add to 100% due to rounding <br />
DashDescription: Information from the tab "Demographics", in the subsection "Deaths by Sex" using the selection "Deaths --> Confirmed", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
   DashWebsite note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />
Date range: Contains ongoing data after 2020-03-26 <br />
Author note: Some percentages are recorded as "<1%", which may need to be transformed before analysis. Post migration to the dashboard on 2020-06-05, values are now presented as raw data instead of percentages <br />

D_Male
* Column: CQ
* Description: Confirmed deceased male COVID cases across Michigan
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_Female
* Column: CR
* Description: Confirmed deceased female COVID cases across Michigan
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_SexNR
* Column: CS
* Description: Confirmed deceased COVID cases across Michigan where sex was unknown/not reported
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided <br />
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

- SECTION DeceasedAge - <br />

Column range: CT through DB <br />
TableDescription: Information from aggregated table "Cases by Age", column "Percentage of Deceased Cases by Age", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
   TableWebsite note: Totals may not add to 100% due to rounding <br />
DashDescription: Information from the tab "Demographics", in the subsection "Deaths by Age Group" using the selection "Deaths --> Confirmed", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
   DashWebsite note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />
Date range: Contains ongoing data after 2020-04-02 <br />
Author note: Some percentages are recorded as "<1%", which may need to be transformed before analysis. Post migration to the dashboard on 2020-06-05, values are now presented as raw data instead of percentages <br />

D_0_19
* Column: CT
* Description: Confirmed deceased COVID cases across Michigan between the ages of 0 to 19
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided <br />
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

D_20_29
* Column: CU
* Description: Confirmed deceased COVID cases across Michigan between the ages of 20 to 29
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_30_39
* Column: CV
* Description: Confirmed deceased COVID cases across Michigan between the ages of 30 to 39
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_40_49
* Column: CW
* Description: Confirmed deceased COVID cases across Michigan between the ages of 40 to 49
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_50_59
* Column: CX
* Description: Confirmed deceased COVID cases across Michigan between the ages of 50 to 59
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_60_69
* Column: CY
* Description: Confirmed deceased COVID cases across Michigan between the ages of 60 to 69
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_70_79
* Column: CZ
* Description: Confirmed deceased COVID cases across Michigan between the ages of 70 to 79
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_80_plus
* Column: DA
* Description: Confirmed deceased COVID cases across Michigan between the ages of 80 to 89
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_AgeNR
* Column: DB
* Description: Confirmed deceased COVID cases across Michigan with unknown/not reported age
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided <br />
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

- SECTION DeceasedOverallAge - <br />

Column range: DC through DF <br />
TableDescription: Information from aggregated table "Age Data of Overall Deceased", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
Date range: 2020-03-27 through 2020-06-06 <br />
Author note: Post migration to the dashboard on 2020-06-05, this data is no longer reported <br />

D_AgeMin
* Column: DC
* Description: The youngest age recorded among confirmed deceased COVID cases, taken from the lower end of the variable "Age Range"
* Values: Integer
* Missing values reason: This value is missing if not reported <br />

D_AgeMax
* Column: DD
* Description: The oldest age recorded among confirmed deceased COVID cases, taken from the higher end of the variable "Age Range"
* Values: Integer
* Missing values reason: This value is missing if not reported <br />

D_AgeAvg
* Column: DE
* Description: The average age of confirmed deceased COVID cases, taken from the variable "Average Age"
* Values: Float, one decimal point
* Missing values reason: This value is missing if not reported <br />

D_AgeMed
* Column: DF
* Description: The median age of confirmed deceased COVID cases, taken from the variable "Median Age"
* Values: Integer
* Missing values reason: This value is missing if not reported <br />

- SECTION DeceasedRace - <br />

Column range: DG through DM <br />
TableDescription: Information from aggregated table "Cases by Race", column "Percentage of Deceased Cases by Age", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
   TableWebsite note: Totals may not add to 100% due to rounding <br />
DashDescription: Information from the tab "Demographics", in the subsection "Deaths by Race" using the selection "Deaths --> Confirmed", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
   DashWebsite note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />
Date range: Contains ongoing data after 2020-04-02 <br />
Author note: Some percentages are recorded as "<1%", which may need to be transformed before analysis. Post migration to the dashboard on 2020-06-05, values are now presented as raw data instead of percentages <br />

D_Native
* Column: DG
* Description: Confirmed deceased COVID cases across Michigan identifying as American Indian or Alaska Native
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_Asian
* Column: DH
* Description: Confirmed deceased COVID cases across Michigan identifying as Asian/Pacific Islander
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_Black
* Column: DI
* Description: Confirmed deceased COVID cases across Michigan identifying as Black or African American
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_White
* Column: DJ
* Description: Confirmed deceased COVID cases across Michigan identifying as Caucasian
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_Many
* Column: DK
* Description: Confirmed deceased COVID cases across Michigan identiyfing as Multiple Races
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_Other
* Column: DL
* Description: Confirmed deceased COVID cases across Michigan identifying as Other
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided

D_RaceNR
* Column: DM
* Description: Confirmed deceased COVID cases across Michigan of unknown/not reported race
* Values: Percentage; Integer
* Missing values reason: This value may be missing if not applicable or not provided <br />

- SECTION DeceasedEthnicityHispanic - <br />

Column range: DN through DP <br />
Description: Information from aggregated tables "Cases by Hispanic/Latino Ethnicity", column "Percentage of Deceased Cases by Ethnicity", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
Date range: Contains ongoing data after 2020-04-02 <br />
Website note: Totals may not add to 100% due to rounding <br />
Author note: Some percentages are recorded as "<1%", which may need to be transformed before analysis <br />

D_Hispanic
* Column: DN
* Description: Confirmed deceased COVID cases across Michigan identifying as Hispanic/Latino
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

D_NonHispanic
* Column: DO
* Description: Confirmed deceased COVID cases across Michigan identifying as Non- Hispanic/Latino
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

D_HispanicNR
* Column: DP
* Description: Confirmed deceased COVID cases across Michigan with unknown Hispanic ethnic affiliation
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided <br />

- SECTION DeceasedEthnicityArab - <br />

Column range: DQ through DS <br />
Description: Information from aggregated tables "Cases by Arab Ethnicity", column "Percentage of Deceased Cases by Ethnicity", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163-520743--,00.html <br />
Date range: Contains ongoing data after 2020-04-17 <br />

D_Arab
* Column: DQ
* Description: Confirmed deceased COVID cases across Michigan identifying as Arab
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

D_NonArab
* Column: DR
* Description: Confirmed deceased COVID cases across Michigan identiyfing as Non-Arab
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

D_ArabNR
* Column: DS
* Description: Confirmed deceased COVID cases across Michigan with unknown Arab ethnic affiliation
* Values: Percentage
* Missing values reason: This value may be missing if not applicable or not provided

---

### MichiganOverview_ProbableCases.csv

CheckedEST
* Column: A
* Description: Data and time (YYYY-MM-DD HH:MM) in Eastern Standard Time (EST) when Author collected data
* Values: Date
* Missing values reason: Unable to get link from the Internet Archive due to an error <br />

Link
* Column: B
* Description: Link to archived page in the Web Archive (WaybackMachine)
* Values: String
* Missing values reason: This value should never be missing <br />
Note: Sometimes pages archived in the Web Archive did not register, in which case the link does not work as expected. Internet Archive doesn't support dashboard archiving, so no data within the Microsoft Power BI dashboard is captured (starting from 2020-06-05). Contact Author for pdf versions of the dashboard to view all captured data pages. 

Date
* Column: C
* Description: Date of contained information, in YYYY-MM-DD format
* Values: Date
* Missing values reason: This value should never be missing <br />

- SECTION CountyOverview - <br />

Column range: D through CO <br />
Description: Information from the tab "Current Status", in the subsection "Covid-19 Cases and Deaths by County" under the section "View Table", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-06-05 <br />

Columns D through CH
* Description: Names of Michigan counties reporting probable COVID cases, in the format CP_<County>
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0" <br />
Note: County is based on the county of residence

PC_MDOC
* Column: CI
* Description: The number of probable COVID cases originating in the Michigan Department of Corrections (MDOC) in Michigan
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_FCI
* Column: CJ
* Description: The number of probable COVID cases originating in the Federal Corrections Institution (FCI) in Michigan 
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_OutState
* Column: CK
* Description: The number of probable COVID cases from out of state in Michigan 
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_NR
* Column: CL
* Description: The number of probable COVID cases with unknown origin in Michigan 
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_TOTAL
* Column: CM
* Description: The derived number of total daily probable COVID cases in Michigan. Obtained by horizontally summing of all county and NR cases in the same row 
* Values: Integer
* Missing values reason: This value should never be missing

PC_Detroit
* Column: CN
* Description: The probable COVID cases occuring in Detroit
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0" <br />
Note: City of Detroit and Wayne County are reported separately. Since Detroit is in Wayne County, the Author has combined both of these numbers in the Wayne county count and included the Detroit-only count after the TOTAL column, for reference.

PC_Notes
* Column: CO
* Description: Additional information posted on the website, or notes by the Author to indicate discrepancies 
* Values: String <br />

- SECTION CaseSex - <br />

Column range: CP through CR <br />
Description: Information from the tab "Demographics", in the subsection "Cases by Sex" using the selection "Cases --> Probable", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-06-07 <br />
Website note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />

PC_Male
* Column: CP
* Description: Probable male COVID cases across Michigan
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_Female
* Column: CQ
* Description: Probable female COVID cases across Michigan
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_SexNR
* Column: CR
* Description: Probable COVID cases across Michigan where sex was not reported
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0" <br />

- SECTION CaseAge - <br />

Column range: CS through DA <br />
Description: Information from the tab "Demographics", in the subsection "Cases by Age Group" using the selection "Cases --> Probable", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-06-07 <br />
Website note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />

PC_0_19
* Column: CS
* Description: Probable COVID cases across Michigan between the ages of 0 to 19
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0" <br />
Note: As of 2020-08-02, this category was split into 2 categories: ages 0 to 9 and ages 10 to 19. In order to preserve ability to compare across dates, these two categories are now summed in the dataset

PC_20_29
* Column: CT
* Description: Probable COVID cases across Michigan between the ages of 20 to 29
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_30_39
* Column: CU
* Description: Probable COVID cases across Michigan between the ages of 30 to 39
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_40_49
* Column: CV
* Description: Probable COVID cases across Michigan between the ages of 40 to 49
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_50_59
* Column: CW
* Description: Probable COVID cases across Michigan between the ages of 50 to 59
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_60_69
* Column: CX
* Description: Probable COVID cases across Michigan between the ages of 60 to 69
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_70_79
* Column: CY
* Description: Probable COVID cases across Michigan between the ages of 70 to 79
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_80_plus
* Column: DZ
* Description: Probable COVID cases across Michigan between the ages of 80 to 89
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_AgeNR
* Column: DA
* Description: Probable COVID cases across Michigan with unknown/not reported age
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0" <br />

- SECTION CaseRace - <br />

Column range: DB through DH <br />
Description: Information from the tab "Demographics", in the subsection "Cases by Race" using the selection "Cases --> Probable", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-06-07 <br />
Website note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />

PC_Native
* Column: DB
* Description: Probable COVID cases across Michigan identifying as American Indian or Alaska Native
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_Asian
* Column: DC
* Description: Probable COVID cases across Michigan identifying as Asian/Pacific Islander
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_Black
* Column: DD
* Description: Probable COVID cases across Michigan identifying as Black or African American
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_White
* Column: DE
* Description: Probable COVID cases across Michigan identifying as Caucasian
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_Many
* Column: DF
* Description: Probable COVID cases across Michigan identiyfing as Multiple Races
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_Other
* Column: DG
* Description: Probable COVID cases across Michigan identifying as Other
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PC_RaceNR
* Column: DH
* Description: Probable COVID cases across Michigan of unknown/not reported race
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

---

### MichiganOverview_ProbableDeceased.csv

CheckedEST
* Column: A
* Description: Data and time (YYYY-MM-DD HH:MM) in Eastern Standard Time (EST) when Author collected data
* Values: Date
* Missing values reason: Unable to get link from the Internet Archive due to an error <br />

Link
* Column: B
* Description: Link to archived page in the Web Archive (WaybackMachine)
* Values: String
* Missing values reason: This value should never be missing <br />
Note: Sometimes pages archived in the Web Archive did not register, in which case the link does not work as expected. Internet Archive doesn't support dashboard archiving, so no data within the Microsoft Power BI dashboard is captured (starting from 2020-06-05). Contact Author for pdf versions of the dashboard to view all captured data pages. 

Date
* Column: C
* Description: Date of contained information, in YYYY-MM-DD format
* Values: Date
* Missing values reason: This value should never be missing <br />

- SECTION CountyOverview - <br />

Column range: D through CO <br />
Description: Information from the tab "Current Status", in the subsection "Covid-19 Cases and Deaths by County" under the section "View Table", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-06-05 <br />

Columns D through CH
* Description: Names of Michigan counties reporting probable deceased COVID cases, in the format PD_<County>
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"  <br />
Note: County is based on the county of residence

PD_MDOC
* Column: CI
* Description: The number of probable deceased COVID cases originating in the Michigan Department of Corrections (MDOC) in Michigan
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_FCI
* Column: CJ
* Description: The number of probable deceased COVID cases originating in the Federal Corrections Institution (FCI) in Michigan 
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_OutState
* Column: CK
* Description: The number of probable deceased COVID cases from out of state in Michigan 
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_NR
* Column: CL
* Description: The number of probable deceased COVID cases with unknown origin in Michigan 
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_TOTAL
* Column: CM
* Description: The derived number of total daily probable deceased COVID cases in Michigan. Obtained by horizontally summing of all county and NR cases in the same row 
* Values: Integer
* Missing values reason: This value should never be missing

PD_Detroit
* Column: CN
* Description: The probable deceased COVID cases occuring in Detroit
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0" <br />
Note: City of Detroit and Wayne County are reported separately. Since Detroit is in Wayne County, the Author has combined both of these numbers in the Wayne county count and included the Detroit-only count after the TOTAL column, for reference

PD_Notes
* Column: CO
* Description: Additional information posted on the website, or notes by the Author to indicate discrepancies 
* Values: String <br />

- SECTION DeceasedSex - <br />

Column range: CP through CR <br />
Description: Information from the tab "Demographics", in the subsection "Deaths by Sex" using the selection "Deaths --> Probable", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-06-07 <br />
Website note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />

PD_Male
* Column: CP
* Description: Probable deceased male COVID cases across Michigan
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_Female
* Column: CQ
* Description: Probable deceased female COVID cases across Michigan
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_SexNR
* Column: CR
* Description: Probable deceased COVID cases across Michigan where sex was not reported
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0" <br />
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

- SECTION DeceasedAge - <br />

Column range: CS through DA <br />
Description: Information from the tab "Demographics", in the subsection "Deaths by Age Group" using the selection "Deaths --> Probable", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-06-07 <br />
Website note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />

PD_0_19
* Column: CS
* Description: Probable deceased COVID cases across Michigan between the ages of 0 to 19
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

PD_20_29
* Column: CT
* Description: Probable deceased COVID cases across Michigan between the ages of 20 to 29
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

PD_30_39
* Column: CU
* Description: Probable deceased COVID cases across Michigan between the ages of 30 to 39
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

PD_40_49
* Column: CV
* Description: Probable deceased COVID cases across Michigan between the ages of 40 to 49
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_50_59
* Column: CW
* Description: Probable deceased COVID cases across Michigan between the ages of 50 to 59
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_60_69
* Column: CX
* Description: Probable deceased COVID cases across Michigan between the ages of 60 to 69
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_70_79
* Column: CY
* Description: Probable deceased COVID cases across Michigan between the ages of 70 to 79
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_80_plus
* Column: DZ
* Description: Probable deceased COVID cases across Michigan between the ages of 80 to 89
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_AgeNR
* Column: DA
* Description: Probable deceased COVID cases across Michigan with unknown/not reported age
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0" <br />
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

- SECTION DeceasedRace - <br />

Column range: DB through DH <br />
Description: Information from the tab "Demographics", in the subsection "Deaths by Race" using the selection "Deaths --> Probable", taken from https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html <br />
Date range: Contains ongoing data after 2020-06-07 <br />
Website note: Data are suppressed when the number of cases is five or below to protect the confidentiality of individuals. The sum of the cases for individual categories may be fewer than the total number of cases due to data suppression <br />

PD_Native
* Column: DB
* Description: Probable deceased COVID cases across Michigan identifying as American Indian or Alaska Native
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

PD_Asian
* Column: DC
* Description: Probable deceased COVID cases across Michigan identifying as Asian/Pacific Islander
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

PD_Black
* Column: DD
* Description: Probable deceased COVID cases across Michigan identifying as Black or African American
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_White
* Column: DE
* Description: Probable deceased COVID cases across Michigan identifying as Caucasian
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"

PD_Many
* Column: DF
* Description: Probable deceased COVID cases across Michigan identiyfing as Multiple Races
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

PD_Other
* Column: DG
* Description: Probable deceased COVID cases across Michigan identifying as Other
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"
Note: As of 2020-08-02, this category is no longer being reported and is left as blank in the dataset

PD_RaceNR
* Column: DH
* Description: Probable deceased COVID cases across Michigan of unknown/not reported race
* Values: Integer
* Missing values: Lack of probable deceased cases at the time of the report represented as "0"
* Missing values reason: This value may be missing if not applicable or not provided <br />
