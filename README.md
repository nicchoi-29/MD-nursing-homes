# Are Maryland Nursing Homes Prepared to Care for a Diverse Older Population?

## What I hoped to accomplish

I iniitally wanted to better understand how nursing homes were taking care of aging immigrants in Maryland. The 
care I was focused on was langauge services and culturally familiar food accommodations. As I contiued to research, I changed the focus from immigrants to speakers of other languages besides English. 

## Overview of Data Analysis Process

- To identify the number of nursing homes throughout the state, I used public data from the Maryland Health Care Commission. Nursing homes are defined as facilities that provide 24-hour and long-term comprehensive care. I filtered only by address. I then used the zip code lookup table on Maryland's open data portal to match zip code to the county. 

- To identify the specific languages spoken (by residents at least 5 years old) in the state, I used Table B16001 at the state level from the U.S. Census 1-Year 2024 American Community Survey. I used this same table to identify speakers with limited Engish proficiency (LEP) by filtering for those who reported speaking English less than "very well." I filtered for this data at the state level because I wanted to provide a snapshot of langauages spoken throughout the state rather than a county- or census-level analysis and avoid making any direct copmarisons with Table S1601 discussed below. Analysis at the county level also helped to reduce the number of suppressed values and margins of error. 

- To identify speakers of other languages besides English who are also 65 years or older, I used Table S1601 at the county level from the 5-Year 2020-2024 American Community Survey. I chose the county level to better understand language needs in the areas surrounding a nursing home. A county-level analysis also helped to reduce the number of suppressed values and margins of error. I also used this table to identify the percentage of LEP (people who report not speaking English "very well") among other language speakers who are also 65 years or older. I tried to avoid making any direct comparison between data from the 1-year and 5-year surveys. I felt that it was important to use both because while Table S1601 breaks down larger language groups(Asian and Pacific Islander, Indo-European, etc.) by age, Table B16001 reports specific langauges but does not do so by age. 


## Skills Used and Key Learning Moments

- This was a frustrating and lengthy project. I ran into a lot of stuck moments, unsure of how to move forward. This was mostly because I was using the wrong data to answer my questions and trying to create map layers in QGIS. I learned about qgis2web and used it to create HTML for one layer but learned that it doesn't work for graduated symbology, only simple. I spent days trying to figure out why qgis2web kept crashing the program before I remembered I should read the actual documentation, where I learned about the inability to export graduated layers. But a TA told me that geographical data doesn't have to be represented geographically and recommended a scatterplot, which helped me to get unstuck and move this project forward. 

- Census data was confusing to work with. I felt like I had to make a lot of judgement calls because of the high margins of error for some estimates and suppressed values.  

## What I Wanted to Do

I plan to continue developing this project in the following ways: 
- Create a tool that people canld use to filter nursing homes by language services provided, how they're provided (on-site translator, translation app, etc.), and types of food accommodations. 
- Identify any patterns in the types of complaints that nursing homes receive, and compare those patterns to county and nursing home demographics.  