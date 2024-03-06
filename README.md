# Geog458-AA1-Final Project
Wi24 Geog 458 GroupAA1 final project

### Group AA1
- Abigail Chinn
- Chaeri Hong
- Yezhen Chen
- Wyatt Stanley
- Elijah Price

## Project idea & format & significance & impacts
We are planning on making a series of maps starting with a broad area and moving to a more localized area, showcasing hospital accessibility. We plan to make a map-based storytelling project with VSCode and Mapbox to publish to GitHub Pages, building our final project off of lab 7. We plan to start with a map of hospitals as points in the United States, and as users scroll down, they will see a second map showing the location of hospitals as points and county populations in Washington State as the choropleth. The third map will show the total number of beds in hospitals in Washington as a choropleth. Lastly, the distance from parcels to hospitals in Washington is color-coded by distance. 

The significance of this project idea is that it demonstrates disparities in hospital access, which play an important role in determining overall health outcomes. These maps will look at how the spatial distribution of hospitals varies across the United States, Washington, and Seattle, to see where the absence of hospitals is. This seeks to highlight existing challenges in hospital access, but also how absence may lead to delayed hospital access, and thus health outcomes.

Our project could generate a negative impact when done because it may show an absence of hospitals in places where a need may not be necessary or may not be a need at such a large level. In our maps, we are looking at how various geographic locations vary in hospital access, and in places where no one is perhaps, we would likely see an absence of hospitals, and thus an advocation for them there. Because we are looking at a small scale, we do not know what the community needs there, if at all. Additionally, we are not looking at how populations are spread out over geographic locations, so more need is likely in places where people are located. We could avoid generating this negative impact by putting a disclaimer. We could also look to analyze specific geographic areas and include data on the population there. We could also show where people may be located and how that may influence hospital accessibility.

## Functions
We will use our maps and data to display hospital availability in the United States and Washington. Using a series of datasets, we will illustrate patterns in the distribution of hospital access in Washington State. As users scroll downward on the webpage, they will be able to view the various maps listed above as they demonstrate hospital accessibility and disparities in access from a country level to a city level. As users hover over data points on the maps, they will be able to see different data points, such as the county population in Washington, hospital numbers within the area, and the county name.

## Data sources
[Washington County population](https://data.wa.gov/demographics/WAOFM-Census-Population-Density-by-County-by-Decad/e6ip-wkqq/about_data)

[Hospitals in Washington](https://geo.wa.gov/datasets/WADOH::hospitals/explore?location=46.138169%2C-118.651792%2C7.23)

[Hospital statistics by state](https://www.ahd.com/state_statistics.html)

[Hospitals in the United States](https://hub.arcgis.com/datasets/geoplatform::hospitals/explore?location=47.635176%2C-122.255440%2C11.41)

[Washington State Counties](https://cartographyvectors.com/map/1396-washington-state-counties)

[Census Tracts](https://data-seattlecitygis.opendata.arcgis.com/datasets/9075e8c912a24c4b9458af8866c72ae7/explore?location=59.801857%2C-99.687557%2C3.71)

[Population Demographic Data](https://data.census.gov/table/DECENNIALDP2020.DP1?g=040XX00US53,53$1400000&d=DEC%20Demographic%20Profile)

## Target audience
We want our audience to be community members. Bottom-up challenges to authority figures as learned from Stand with #StandingRock are where ordinary people can ignite change or create momentum. Those in government and public policy will be unlikely to build hospitals in areas where there aren't already because of high costs, so hospitals need to be pushed by community voices that unite together. The existence of hospital services that provide essential healthcare services will be important for community members who live in those areas to get services they may need. Informing community members and the public with these facts may bring the topic of medical care up to the table in areas lacking hospital availability. 

Lastly, one of the potential audiences is governmental officials. Informing them of the up-to-date distribution of hospitals locally and nationwide may bring some positive changes. 

## Multimedia
[Hospital beds](https://th-thumbnailer.cdn-si-edu.com/F6MN7vfNd8zeHpNYi58PzoC_OAo=/1000x750/filters:no_upscale()/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer/b4/c6/b4c65fd0-01ba-4262-9b3d-f16b53bca617/istock-172463472.jpg)

[UW Medicine building](https://www.usa.skanska.com/4a532f/globalassets/externalcontent2/project/university-of-washington-medical-center-montlake-tower-expansion/ab603c15-f473-47cb-a54c-c5ba53b2558d.1.jpg?height=524&width=932&scale=both&mode=crop&bgcolor=)

[UW medicine building2](https://images.seattletimes.com/wp-content/uploads/2023/06/06092023_UW_Hospital_Montlake-2016_152832.jpg?d=2040x1386)

[Ambulance](https://zhl.org.in/blog/emergency-ambulance-services-intelligent-transportation-systems/)

[Hospital](https://www.va.gov/puget-sound-health-care/locations/seattle-va-medical-center/)

## Geo-narrative
- Map projection:
- Map zoom levels: 4 (US), 7 (WA), 11 (Seattle)
- Center: [-109.4151140079552, 41.25017612415869] (US), [-122.32924428512132, 47.646212989022125] (WA), [-122.3659068281188, 47.661669543756304] (Seattle)
- Description of the base map planned to use: [light mono-color grey](mapbox://styles/mapbox/light-v10)
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
- Transitions: zoom in from place to place when geographical location changes, however, for same ones (like US), zoom will remain the same ; Scroll to transit among maps and pages. 
