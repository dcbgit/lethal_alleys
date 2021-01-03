# Lethal Alleys
## Tornado Alley vs Dixie Alley, a comparison of tornadoes from 2000-2018
## TABLE OF CONTENTS
* [INTRODUCTION](#introduction)
* [THE DATA](#the-data)
* [METHODOLOGY](#methodology)
* [TOOLS USED](#tools-used)
* [SOURCES](#sources)
* [TABLEAU STORY](#tableau-story)

## INTRODUCTION

The National Oceanic and Atmospheric Administration (NOAA) reports that the United States experiences an average of 1,000 tornadoes per year.  Most of these tornadoes are found in the Great Plains in an area, unofficially, known as Tornado Alley. The second most vulnerable area for multiple tornadoes to strike is in the southern United States in what is lesser known as Dixie Alley.  

This capstone project will use publicly available data from NOAA to analyze both Tornado Alley and Dixie Alley tornadoes in terms of frequency, magnitude, number of fatalites and the time of day to understand which “Alley” is more dangerous.

I selected this project because I find this topic and all naturally occurring disasters for that matter, fascinating. I’ve worked as a disaster management program manager and have witnessed the catastrophic impact such events have on people’s lives. This capstone project is an opportunity for me to provide compelling information, powered by data to save lives.

## THE DATA

Data from NOAA's Storm Prediction Center was used to look at the number, location and magnitude of tornadoes from 2000 - 2018.
To find the number of fatalities by year and location of occurrence, 18 .pdf files were pulled from the National Weather Service and converted, in python, to one .csv file.  
States were grouped by Tornado Alley (IA, KS, MO, NE, OK, TX) and Dixie Alley (AL, AR, GA, LA, MS, TN) and analyzed.
 
## METHODOLOGY



Fact based presentation in Tableau that draws conclusions from the analysis and makes recommendations to federal and state legislatures responsible for governing residential construction, city planners and residential building codes committees on possible adjustments to construction codes and standards. The end goal is to provide information that will serve to limit causalities in homes resulting from tornadoes.  The presentation will be delivered in a zoom environment and supported by visualizations to include histograms, line charts, and maps.

Data Sources
-	NOAA Storm Events Database https://www.ncdc.noaa.gov/stormevents/
-	International Code Council https://www.iccsafe.org/
-	Manufactured Housing Institute https://www.manufacturedhousing.org/building-codes-and-standards/
-	US Census Bureau https://www.census.gov/construction/nrc/index.html
-	US Census Bureau https://www.census.gov/data/tables/2010/dec/density-data-text.html

Known Issues and Challenges

Anticipated Challenges	Management Plan
Lack of confidence in coding skills necessary to draw meaningful conclusions from the data within the given time constraints.
	Seek assistance from the experts, early and often.
Locating concrete data to support changes to existing building codes. 	Dig deeper into FEMA datasets as it’s highly plausible that this issue has been raised.
Locating convincing data to support the obvious - why manufactured homes are a death trap in a tornado.	Keep searching, it’s likely that the answer will come from “web scraping” techniques.
Its known that unknown challenges will arise. 	As there are still many competing priorities before full devotion to this project can been applied, start early.
Request for data or api key	Presently unknown
Known data cleaning steps	Presently unknown

![alley](png/map_TA_DA.jpg)
