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
*Map of Bokaro District: Panchayatwise Distribution Map of Expected Incoming Migrants* 
This is the dashboard of panchayatwise distribution on the map of Bokaro district of estimated incoming migrants across districts. Larger the circle in the geographic area, greater is the expected incoming migrant population. Major clusters can be identified using this. (Please note that this is a screenshot of an interactive dashboard with several advanced features).

Major challenges were addressed as follows:
1. **Resource Allocation**: Identifying the regions within the district where migrants will ultimately settle to facilitate the allocation of resources such as PPE kits, quarantine centers, and food distribution units. Using ArcGIS, density maps were generated to locate major clusters and determine the estimated number of migrants in each area.

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Food%20Facility%201%20-%20Dal%20Bhat%20Kendras.PNG?raw=true)
*Map of Bokaro: Food Distribution Facilities I - Dal Bhat Kendras*

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Food%20Facility%202%20-%20Didikitchens.PNG?raw=true)
*Map of Bokaro: Food Distribution Facilities II - Didi Kitchens*

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Health%20Facilities.PNG?raw=true)
*Map of Bokaro: Health Facilities*

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Schools.PNG?raw=true)
*Map of Bokaro: Schools*

Major clusters of migrants are identified and logistics are planned accordingly. Location of food distribution centers and quarantine centers was optimally selected usingsocioeconomic data of the district.

2. **Rescue Operations**: Visualizing the stranded population concentration across the country to help with bus route planning.

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Stranded%20Migrants%20-districtwise.PNG?raw=true)
*Map of India: Stranded Residents Districtwise *

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Stranded%20Migrants%20-statewise.PNG?raw=true)
*Map of India: Stranded Residents Statewise *

The above figures illustrate the distribution of stranded Bokaro residents by district and state. Larger circles represent higher numbers of stranded individuals. A total of 38,085 people were stranded, with 19,846 expected to return.

3. **Containment Zone Mapping**: Managing the virus epicenters by mapping the active containment zones and analyzing demographics such as age distribution and population density to provide necessary resources to vulnerable sections.
![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Hotspots.png?raw=true)
*Map of Containment and Buffer Zones*

A 3km region around the virus epicenter was designated as acontainment zone. The image shows a dedicated view from the main dashboard used for closely monitoring the status of containment zones

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Demographics%20Containment%20Zone.png?raw=true)
*Demographics for Containment Zone*

Demographic data was leveraged to facilitate the distribution of essential supplies like sanitary pads and medicines inside the containment zones.

## Quarantine Management System
**Background** All the people who were arriving from different parts were advised home quarantine of 14 days as per MHA guidelines. To ensure that this is strictly followed and to monitor it was a big challenge in itself.

**Overview** A quarantine management system was also developed to digitally monitor that the migrants arriving from red zones and hotspots are following quarantine surveillance guidelines.

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/QMS.png?raw=true)
*Home Quarantine Management Dashboard*

**Solution** 
- Ground level workers or Sahiyas present in every village of the district were assigned the job of monitoring the health status and home quarantine of the migrants. But,there was no mechanism to check whether the Sahiyas were actually going to check all these migrants on a daily basis to ensure their home quarantine.
- We have more than 700 villages and 10-15000 people to monitor. So, we digitalized the process. We already had the contact details of the migrants so we provided them a pre filled web page with the names and lists of these migrants already written there. We also sent an OTP to all these migrants, then we instructed the Sahiya to write the OTP and enter it on our webpage beside the correct name.
- If the OTP is correct then they will automatically get a “Correct” message and “Wrong OTP” if the OTP is wrong. This ensured that the Sahiya actually went and checked on that person and this helped the administration strengthen its network on the ground level. Initially, there were low percentages of OTPs verified which helped the admin strict its vigil on such parts.

## KAAMGAAR – Skill Mapping and Employment portal for Migrants

We were collecting the skill/professional data of the incoming migrants at the time of their re-entry into the district.

In the final stage of lockdown, we have a huge database of 13000 skilled and unskilled migrant workforce within the Bokaro district. Now, the next challenge is to provide them jobs locally as because of the harassment and trauma these people had faced they wont be willing to return back to their source states. This is also in alignment with the vision of our Hon’ble Prime Minister Narendra Modi to make “vocal which is local”. This will give a huge boost to the industries present locally to start into new ventures and also manage their labour crunch because of the migrants of other states who have left Bokaro.

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Skill%20Mapping%20Bokaro.png?raw=true)
*Skill Mapping Pie Chart*

We had also collected the consent of the people to work in MNREGA schemes and shockingly about 78% of the total number of people were interested, clearly highlighting the desperateness of the people to find livelihood opportunities.

![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Skill%20Mapping%20Bokaro%202.png?raw=true)
*Skill Mapping Tabular*

We developed a [web portal](https://tinyurl.com/kaamgaar-bokaro) which will act as a skill exchange centre for the district. We have populated it with the dataset of the migrant workforce we had with people belonging to various traits like carpentry, electricians, drivers, construction workers, tailors, cooks etc. In this portal we have also created separate sections for people to provide with bulk requests which our team handles specifically.

We have also provided a search box with address, skill and gender filters to allow potential employers to freely search from the database and get in touch with their potential employees. This portal is completely free of cost and the main aim is to provide employment and jobs to the distressed migrants and also to push the local economy stuck due to the prolonged crisis and shutdown.


![GitHub Logo](https://github.com/chitransh1998/SARAL/blob/main/Kaamgar%20Portal.png?raw=true)
*Kaamgar Portal Homepage*
