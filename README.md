# SARAL
About Covid-19 response

## Background: 
About, 20,000 people stranded across the nation due to the lockdown belonging to Bokaro
District. Bokaro district is in the state of Jharkhand, India with a population of about 25 Lakhs divided
into two subdivisions, 9 blocks and 250 panchayats. These stranded people included labour,
medical migrants, tourists, students etc. After the MHA guidelines, it was now possible for
these people to be transported back to their native places. The main challenge was to plan
the arrival of these people back into the district safely and also ensure their surveillance.

## Overview
A system was designed to plan rescue operations for stranded migrants and
efficiently record details of the incoming migrants for further surveillance and planning
of relief measures.

## Data Collection
1. **Incoming Migrant Data**: A digital form was created that captured personal details, skill information, and travel history of migrants, and field staff at 20 entry points into the district like railway stations and highways were trained to fill this form. 
2. **Stranded Migrant Data**: Call centers were set up to receive information on migrants stuck at various locations in the nation.   
3. **Demographic data** of the region was obtained from ESRI (Environmental Systems Research Institute). 

## Data Analysis
A centralized real-time dashboard using a Geographical Information System tool - ArcGIS and Google AppScripts was created, featuring various geospatial views and trends.
![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Incoming%20Migrants%20-%20Panchayatwise.PNG?raw=true)
*This is the dashboard of panchayatwise distribution on the map of Bokaro district of estimated incoming migrants across districts. Larger the circle in the geographic area, greater is the
expected incoming migrant population. Major clusters can be identified using this. (Please note that this is an interactive dashboard with several advanced features).*
Major challenges were addressed as follows:
1. **Resource Allocation**: Identifying the regions within the district where migrants will ultimately settle to facilitate the allocation of resources such as PPE kits, quarantine centers, and food distribution units. Using ArcGIS, density maps were generated to locate major clusters and determine the estimated number of migrants in each area.
2. **Rescue Operations**: Visualizing the stranded population concentration across the country to help with bus route planning.
3. **Containment Zone Mapping**: Managing the virus epicenters by mapping the active containment zones and analyzing demographics such as age distribution and population density to provide necessary resources to vulnerable sections. 
