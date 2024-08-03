This is a project analyzing New York State Department of Labor labor projections within a variety of data positions in a 10 year period from 2020 to 2030. 
The dataset will be analyzed by using BigQuery SQL and an excerpted version of the original dataset which could be found on the New York State Department of Labor
website by using this link: https://dol.ny.gov/employment-projections. The specific dataset is called, "Statewide Projections".

You can view my Tableau Public dashboard using this link: https://public.tableau.com/app/profile/andrew.singh4959/viz/OccupationalForecastforDataRelatedRolesinNewYorkState/Dashboard1

The inspiration for the project comes from the economic recession we are currently undergoing in 2023. As a data analyst I am curious about the labor market in
the coming years in New York State overall, as the field of technology and the industry itself has experienced massive layoffs across small to large, enterprise employers
such as Salesforce, Google, Meta, and many more. This project will be informative for not only myself but for other data professionals in understanding where the most 
growth will happen in their respective industry as well as learning how to best prepare for the future needs of the workforce. By the end of this project, 
my following goals are to: 
  1. Understand the growth of each of roles, in terms of annual hiring trends
  2. Income distribution across the spectrum of the roles  depending on level of experience
  3. Be able to support others in learning about the latest market trends based on labor data

Cleaning the dataset
The original dataset had over 700+ occupational titles, for the analysis I was only interested in the roles with the word "analyst" in the title or roles in the data/techology industry. 
The method of cleaning the dataset was performing a search for all the roles with the titles I was interested in and removing the remaining titles that was 
not necessary for the project. The final spreadsheet was exported as a CSV file and imported into BigQuery for SQL analysis. 
