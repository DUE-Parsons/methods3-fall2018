---
layout: project-page
title: "Development or Disparity: The case of Lahore, Pakistan"
linkname: development-or-disparity-the-case-of-lahore-pakistan
author: "Khadija Munir"
tagline: "Investigating the mega infrastructures and legal encroachments which are influencing the development of Lahore today. "
location:
    - place: Lahore, Pakistan.
project-link:
    - href: https://thenewschool.carto.com/u/munik056/builder/b5f1c005-5d26-4ad8-a1d7-f4f97809e6f1/embed
    - href:  https://thenewschool.carto.com/u/munik056/builder/63da5ff4-b384-403c-a83c-922837164d9e/embed
    - href:  https://thenewschool.carto.com/u/munik056/builder/a31544ca-662c-4e33-b48e-5242e0fec61e/embed
tags:
    - tag: Right to the city
    - tag:  Transportation
    - tag:  Infrastructure
    - tag:  Urban Planning
    - tag:  Public Realm
    - tag:  Public resources
    - tag:  Privatization
    - tag:  Displacement
    - tag:  Urban renewal
    - tag:  Real-estate speculation
    - tag:  Foreign investment
    - tag:  Debt
    - tag:  Public land
    - tag:  Community development
    - tag:  Community engagement
    - tag:  Environmental Sustainability
    - tag:  Urban Development. 
thumbnail-path: img/development-or-disparity-the-case-of-lahore-pakistan/QyxV1Ez.jpg
img-folder: ../../img/development-or-disparity-the-case-of-lahore-pakistan/
timestamp: 12/7/2018 22:12:32
---
As the 14th largest city in the world, with a population of 11.13 million people, Lahore, Pakistan has increased almost 30 percent in size in the past decade. In addition to this, there is huge foreign investment pouring in the city in form of mega infrastructure projects that are changing the urban fabric and the lived experience of the city. My primary objective was to investigate the various forces which influence the development of Lahore today, of which the most common ones are the foreign funded Infrastructure projects such as the Orange train and Red Metro bus, and an unprecedented increase in private housing societies, which are no less than legal encroachments on previously rural land. 

Working on two scales, City-wide and neighbourhood scale. My major emphasis was on the relationship of transportation infrastructure networks with existing urban sprawl and their impact on each other. The biggest challenge was to acquire data, since there is not a lot of open data available to public in Pakistan. Most of the demographics are also not digitized and had to be manually made into data sheets by me for my research purpose. The long term end goal is to develop an Atlas of development patterns of lahore, which brings together all the forces affecting the development patterns and urban sprawl in Lahore. Though mapping and research analysis, I tried to detect the underlying trends of disparity in infrastructure design and low income settlements. 

The first step was to find data, that could be made useful for my research purposes. Even with myriad of search engines available, very few of them had data available on Lahore. Successful digital data sources included OSM, Natural Earth Data, Urban atlas and google my maps. Other then these,I went through extensive online research and probing around already mapped data to obtain data sets and shape files. I used multiple websites and resources such as developer tools, open refine and feature server. Obtaining Union Council, District, City and national boundary shapefiles of Pakistan using feature server downloading. I categorized to obtain city data information and demarcation. Intersecting with Lahore boundaries to keep the data, geography-specific. 

After obtaining some base layers and data files, I resorted to map the urban sprawl in the city using data from the Urban Atlas for a macro understanding of the city. The map below shows the extensive change in the city’s boundary over the course of 20 years. 
![]({{ page.img-folder }}JqG3WVh.jpg)

Mapping private housing projects in the city, onto the same map, also helped me confirm my intuition that private housing societies had a strong role to play in the city’s uncontrolled sprawl. 

![]({{ page.img-folder }}3zINYCt.jpg)

See full online Urban Sprawl carto map here. 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/munik056/builder/b5f1c005-5d26-4ad8-a1d7-f4f97809e6f1/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Next , I zoomed in at an intermediate scale to map the existing and future transport infrastructure. Using data from OSM, I was able to overlay formal road infrastructure in quite detail, and categorized according to type as well. Next step was to spatialize informal forms of transport, such as rickshaws, bus stops, taxi stands etc. These were then overlaid with land use maps data derived from feature server tool, to start understanding how the land use affects the way informal modes of transport are developed in low income neighbourhoods.

![]({{ page.img-folder }}D4E0JT5.jpg)

 By mapping land use in the same map, I seek to uncover the influence of both formal/informal ways of public transport that the citizens use and assess its effectiveness. 

![]({{ page.img-folder }}sLR9Lnw.jpg)

See full online transportation analysis map here. 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/munik056/builder/63da5ff4-b384-403c-a83c-922837164d9e/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>


A major roadblock was to create a comprehensive choropleth map of population density. The data available online had contrasting administrative boundaries and incomplete data set for population, hence could not be relied on to give an accurate population distribution. After rummaging through various statistics books released by the government, I decided to use the 2017 population census boundaries for an accurate data set, and match it up with census document to build my own data set. 

![]({{ page.img-folder }}GoSOywa.jpg)

While this was a painstakingly long process, it helped me create and accurate data set for population down to Union Council. 

![]({{ page.img-folder }}J6nsW23.jpg)

Using this digitized data, I was able to generate the following Choropleth for Population Density. 

![]({{ page.img-folder }}6LxlBcO.png)

The next step was to map the mega transportation projects. I resorted to geo referencing the map diagrams available for the unbuilt train lines and tracing manually from OSM the existing train lines. 

![]({{ page.img-folder }}8PkkByF.jpg)


Next step was to add existing route and feeder buses stops to the same map and assess the “need” of expensive train lines being laid out in the city. 

![]({{ page.img-folder }}CYiG8WO.jpg)


After creating a comprehensive infrastructure  map, I overlaid it with population density to study which areas are underserved as well as the most congested areas in the city. 

![]({{ page.img-folder }}fkFr0MY.jpg)
 
Further to my stated hypothesis, a buffer of 1 km., approx was created in QGIS, to see which Union councils are in close proximity to the train lines and have more chances of using them. 

![]({{ page.img-folder }}Pq8qXaX.jpg)


Before I could predict strong trends in development patterns, I mapped the private housing developments in the city onto the same map to see if there was a direct correlation between the beneficiaries and targeted audience of such mega transport projects. 

![]({{ page.img-folder }}3yeRCI4.jpg)

See full online carto map here.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/munik056/builder/a31544ca-662c-4e33-b48e-5242e0fec61e/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Amalgamating and Quantifying the strong factors which seemed to play a role in the city’s development, helped me zoom in further on a micro scale and detect the most vulnerable neighbourhoods as well as hotspots for further “private” investment in this process. It also helped me detect outliers, which on the outward seem like they would have no impact of the mega infrastructure projects, but in actual can be the next “prime” locations for private real estate investment. 

![]({{ page.img-folder }}1dGqGCy.jpg)

![]({{ page.img-folder }}eSNMha6.jpg)

![]({{ page.img-folder }}KO9l3pI.jpg)

![]({{ page.img-folder }}ub9fBtq.jpg)

![]({{ page.img-folder }}EViAcSB.jpg)

![]({{ page.img-folder }}5SgblaJ.jpg)

All the analysis was taken to carto to be hosted as interactive, additive online maps, that helps the users create a narrative from the city-wide  scale to zooming in on the Neighbourhood scale. Accompanying pop ups with information about the infrastructure projects as well as the private real estate housing developments. The idea is to use it as an Atlas to visualize the narrative of development and urban renewal’s impact on Pakistan as well as form a useful resource for citizen action and claim. 
