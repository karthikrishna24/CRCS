# Multi State Cooperative Socities Dashboard | POWER BI

## Introduction
During the hackathon, I successfully designed and developed a comprehensive dashboard for the Central Registrar for Cooperative Societies (CRCS) in India. The dashboard was created to streamline the registration process, handle amendments and appeals, and manage annual returns for registered societies, in accordance with the MSCS Act of 2002. The central aim of the hackathon is to create a BI framework to apply their real data and not about the insights.

## Dashboard
Link for the Dashboard - https://app.powerbi.com/view?r=eyJrIjoiYmY1ZWQ1M2MtNTk0Yi00MmIxLWI0YTgtNjI2OGVhOWM1Y2MzIiwidCI6ImZmYTY0YWRkLTQyMDAtNGFhYy1iMzA4LWY5ZDk4ZTYzYzZmYiJ9

![Screenshot 2023-07-27 212041](https://github.com/karthikrishna24/Multi_State_Cooperative_Societies_Dashboard-POWERBI/assets/111265282/967e9b72-7627-4bd2-aa11-7f2ed877d331)

## Overview Of Dashboard
The consumer can get insights about the registered societies 
such as the distribution of Sectors, Registered area, operating area, and much more from the 
comprehensive interactive dashboard. This Dashboard will be helpful to track the progress of 
the sectors and regions over a period of time.

## About Data
The dataset initially contained errors, which were manually cleaned and imputed 
to ensure quality results from the dashboard. These errors included missing district names 
and changes in data types. Created Latitude and Longitude feature for specifying geographical 
location. There may or may not be minor errors in the output due to the quality of the data. 
The cleaner the data, the higher the likelihood of producing a higher quality output.

## Visuals from the Dashboard

- KPIs & Metrics:
   * No of Registered Society – From this, the count of registered Societies to date can be observed and different views can be obtained by using the filters.
   * No of Unique Registered Society – From this, the distinct count of States registered by the societies can be observed and different views can be obtained by using the filters.
   * No of Unique Operating Area – From this, the distinct count of areas that are being operated by the societies can be observed and different views can be obtained by using the filters.
   * No of Unique Sectors – From this, the distinct count of existing Sectors can be observed and different views can be obtained by using the filters.
   * Popular Sector – From this, the most popular sector can be observed, i.e., The sector which has more no of societies, and different views can be obtained by using the filters.
   * Avg Area of Operation – From this, the average count of operating area for a society can be observed, i.e., on average how many areas are being operated by a single society and different views can be obtained by using the filters.
   * Avg Society Age – From this, the average Age of the society can be observed, i.e., On average how old a Society is and different views can be obtained by using the filters.

- Charts and Maps:
   * Count of CRCS by Sector – From this column chart the no of registered societies by sector type can be obtained. By using the filters, we can narrow down the results from the chart.
   * Count of CRCS by State and District (Drill Down) – From this, the no of registered societies by State can be obtained, and by using the Drill Down option each State can be drilled down into districts. By using the filters, we can narrow down the results from the chart.
   * MSCS Population – From this map, we can observe visually where the societies are registered. Other than the filters, we can click the desired state like a filter to get an overall quick insight from the dashboard.
   * Area of operation by sector – From this map, we can visually observe the areas in which the registered societies are operating along with the sector type. By using the legends, we can differentiate the sectors and different views can be obtained by using the filters. For e.g., Let there be a society call ‘abc’, from this map areas in which the society are being operated can be obtained.
   * Count of Society by Region – From this chart, the count of the registered society region-wise can be obtained. Other than the filters, we can click the desired Region column like a filter to get an overall quick insight from the dashboard.

- Table & Others:
   * Table – From the table, the Name of the registered, Date of Registration, Address of the society, Sector type, Areas of operation, and its count can be viewed. By using the search bar, you can search with desired existing society names to get more details about them in the table.
   * Newly Registered CRCS – From this scrolling visual which is present between the filters and metrics, the top 5 newly registered society names can be observed. By using the search bar, you can search with desired existing society names to get more details about them in the table.

- Interactive feature of Dashboard
   * This whole Dashboard is an interactive one, i.e., other than filters, by clicking a specific column 
in the column chart specific or clicking a location in map, the whole dashboard will be drilled 
down to that particular attribute. For e.g., If you select a specific state like ‘Tamil Nadu’, the 
whole dashboard is drilled downed according to the ‘Tamil Nadu’. Likewise, every chart is an
interactive one.


## Insights from the Dashboard (examples)

* There are 100 registered societies among the 18 states. So that we could say, on 
average there will be 5.55 societies in a State.
* Among these 100 societies, the societies are distributed into 13 Sectors. So we could 
say, on average there can be 7.7 societies in a Sector.
* Talking about the sectors, the Agro sector is leading with 54 societies whereas Dairy
& Tourism are lagging with only 1 Society. Now, by varying the year filter we can 
observe that during 2016-2018 there were only four sectors. Among them, 
Cooperative Bank is leading and all the other sectors are also equally performing well.
* Maharashtra is the state which has a high no of registered societies, whereas Assam, 
Jammu and Kashmir, Karnataka, Punjab, Uttarakhand, and West Bengal are having 
only one society. We know that the Agro sector is the popular sector, now by filtering 
by Agro Sector, it can be observed that Uttar Pradesh is the major contributor.
* From the Area of operation Map, it can be observed that the operation is distributed 
all over India and that too mostly in the Northern part of India. From this, we could 
say that the Southern region needs more contributions from the societies. By using 
the Sector type filter, the distribution of sector performance can be observed from the 
map for further analysis.
* From the MSCS Population map, it can be observed that the societies are covering 
64% of India. So, it can be encouraged to make contributions from the other remaining 
states to boost the growth of India.
* In this 64%, the majority of states are from the Western region, and on the other hand, 
Easter and Northeaster regions are less.
* It can be observed that on average 2.92 areas are operated by a Society, which is 
decent but, considering the growth of India, the operating area per society can be 
increased to boost for greater growth of our India



