# Geog458-AA1-Final Project
Wi24 Geog 458 GroupAA1 final project

### Group AA1
- Abigail Chinn
- Chaeri Hong
- 
- 
- 

## Project idea & format & significance & impacts
We are planning on making a series of maps starting with a broad area and moving to a more localized area, showcasing hospital accessibility. We plan to make a map-based storytelling project with VSCode and Mapbox to publish to GitHub Pages, building our final project off of lab 7. We plan to start with a map of hospitals as points in the United States, and as users scroll down, they will see a second map showing the location of hospitals as points and county populations in Washington State as the choropleth. The third map will show the total number of beds in hospitals in Washington as a choropleth. Lastly, the distance from parcels to hospitals in Washington is color-coded by distance. 
The significance of this project idea is that it demonstrates disparities in hospital access, which play an important role in determining overall health outcomes. These maps will look at how the spatial distribution of hospitals varies across the United States, Washington, and Seattle, to see where the absence of hospitals is. This seeks to highlight existing challenges in hospital access, but also how absence may lead to delayed hospital access, and thus health outcomes.

## Functions
We will use our maps and data to display hospital availability in the United States and Washington. Using a series of datasets, we will illustrate patterns in the distribution of hospital access in Washington State. As users scroll downward on the webpage, they will be able to view the various maps listed above as they demonstrate hospital accessibility and disparities in access from a country level to a city level. As users hover over data points on the maps, they will be able to see different data points, such as the county population in Washington, hospital numbers within the area, and the county name.

## Data sources
[Washington county population](https://data.wa.gov/demographics/WAOFM-Census-Population-Density-by-County-by-Decad/e6ip-wkqq/about_data)

[Washington health Districts from WSDOH](https://geo.wa.gov/datasets/WADOH::lhj/explore?location=47.022273%2C-121.249930%2C8.66)

[Hospitals in Washington](https://geo.wa.gov/datasets/WADOH::hospitals/explore?location=46.138169%2C-118.651792%2C7.23)

[Hospital statistics by state](https://www.ahd.com/state_statistics.html)

[Covid cases/deaths by county](https://geo.wa.gov/datasets/99d6ae7787bc4a739c7885eb5ca25b37_0/explore?location=47.140544%2C-119.860715%2C8.11)

[Hospitals in the United States](https://hifld-geoplatform.opendata.arcgis.com/datasets/geoplatform::hospitals/about)

[Parcels in Washington](https://geo.wa.gov/datasets/e8f2df3ed92843738f3dd778e92e93fc/explore)

[Washington State Counties](https://cartographyvectors.com/map/1396-washington-state-counties)

[States](https://hub.arcgis.com/datasets/1b02c87f62d24508970dc1a6df80c98e/explore?location=27.635228%2C-101.458575%2C3.68)

## Target audience
We want our audience to be community members. Bottom-up challenges to authority figures as learned from Stand with #StandingRock are where ordinary people can ignite change or create momentum. Those in government and public policy will be unlikely to build hospitals in areas where there aren't already because of high costs, so hospitals need to be pushed by community voices that unite together. The existence of hospital services that provide essential healthcare services will be important for community members who live in those areas to get services they may need. Informing community members and the public with these facts may bring the topic of medical care up to the table in areas lacking hospital availability. 

Lastly, one of the potential audiences is governmental officials. Informing them of the up-to-date distribution of hospitals locally and nationwide may bring some positive changes. 

## Multimedia
[Hospital beds](https://th-thumbnailer.cdn-si-edu.com/F6MN7vfNd8zeHpNYi58PzoC_OAo=/1000x750/filters:no_upscale()/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer/b4/c6/b4c65fd0-01ba-4262-9b3d-f16b53bca617/istock-172463472.jpg)

[UW Medicine building](https://www.usa.skanska.com/4a532f/globalassets/externalcontent2/project/university-of-washington-medical-center-montlake-tower-expansion/ab603c15-f473-47cb-a54c-c5ba53b2558d.1.jpg?height=524&width=932&scale=both&mode=crop&bgcolor=)

## Geo-narrative
- Map projection:
- Map zoom levels: X (US), X (WA), X (Seattle)
- Center: X (US), X (WA), X (Seattle)
- Description of the base map planned to use:
- Description of thematic layers to make: 
  1. Hospitals in the US as point data
  2. Hospitals in WA as points and County Population in WA as choropleth
  3. Total Beds in Hospitals in WA as choropleth by county
  4. Distance from Parcels to Hospitals in Seattle as choropleth
- Proposed interactive functions:
- Storyline:
  1. Cover page/intro
  2. Map Flow: 
     a. Hospitals in the US 
     b. Hospitals in WA and County Population in WA 
     c. Total Beds in Hospitals in WA 
     d. Distance from Parcels to Hospitals in Seattle
  3. Ending/conclusion
  4. Footer
- Scenes:
  - 0
    - Map: Hospitals in the US as points
    - Associated script:
    - Multimedia:
  - 1
    - Map: Hospitals in WA as points and County Population in WA as choropleth
    - Associated script:
    - Multimedia:
  - 2:
    - Map: Total Beds in Hospitals in WA as choropleth by county
    - Associated script:
    - Multimedia:
  - 3:
    - Map: Distance from Parcels to Hospitals in Seattle as choropleth
    - Associated script:
    - Multimedia:
- Transitions: zoom in from place to place when geographical location changes, however, for same ones (like US), zoom will remain the same
