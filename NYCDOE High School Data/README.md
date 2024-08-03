NYCDOE-High-School-Data
This is a project repository containing SQL code specifically pulling data from three NYCDOE datasets looking at NYC High Schools - their demographics of the student population, graduation rates, and breaking down those trends by borough.

**Overview

What inspired this project? I was thinking about an SQL project I could use NYCDOE datasets to analyze large trends across the largest education system in the United States with 1.1 million students. I wanted to focus on specifically high schools within New York City as this is an interesting area where many policies are developed to help prepare students for college readiness, college success, and career exploration. In fact, many nonprofits within New York City exist serving the high school student population within with the same areas listed above, as students often lack the resources necessary to improve their understanding of college or career choices post-graduation. In this analysis, I seek out to gain a holistic understanding to see where do the high school student population within New York City stand when it comes to these critical areas.

You can view my full dashboard using this link: https://public.tableau.com/shared/MJ2YRMY8J?:display_count=n&:origin=viz_share_link

**Datasets For the datasets - I used information from three different datasets provided by the DOE InfoHUB and NYC Open Data.

2021 NYC High School Directory - I used the 2021 NYC High School Directory to find out how many high schools exist within the NYCDOE educational system and to gain a broader understanding of how those schools perform in terms of college readiness, attendance, academic success, and many other factors. This dataset offers a descriptive understanding of what the high school has to offer for prospective high school students and their families. The link for the dataset is :(url).

NYCDOE Demographic Snapshot - I used the NYCDOE Demographic Snapshot to provide the demographic information for all high schools within the NYCDOE educational system. This dataset contains information describing the race/ethnicity and gender characteristics of the student population, total enrollment per grade level and the school itself, along with the amount of students in the poverty and are economically disadvantaged. The link for the dataset is (url).

2021 NYC Graduation Rates - I used the NYCDOE 2021 Graduation Rates spreadsheet to provide the graudation information for the high schools within New York City. This dataset contains the important characterisitcs of how many students graduated the high school, the graduation rate for specific hgih school diplomas such as regents and advanced regents, while at the same providing the total percentage and count of students dropping out from the high school. The link for this spreadsheet is found (url):https://infohub.nyced.org/reports/school-quality/information-and-data-overview.

**The process for analyzing the datasets. For the datasets I used, I decided to focus on only on the high schools within New York as this would be easier to analyze the major trends I was interested in figuirng out for the school year of 2020-2021.

**Steps to prepare the datasets for analysis

As each of the datasets contains multiple tables within the workbook, I deleted tables that were not necessary and providing information that was necessary to pull using SQL.
By using the DBN code present in the 2021 NYC High School Directory, I was able to find all of the high schools in the NYCDOE Demographic Snapshot dataset which allows me to see the demographics for all high schools.
Lastly, for the 2021 NYC High School Directory, I removed multiple columns that did not provide the information I was looking to use in the analysis.
**Developing KPI Questions For many of the questions I developed, I wanted to find larger trends by the borough, the top performing schools, and schools with a high economic need index and graduation rate. For this section, I devised multiple SQL queries to the multiple questions I created for each dataset and then for multiple datasets using left joins for one or more tables. I used Google Big Query to analyze the datasets using SQL.
