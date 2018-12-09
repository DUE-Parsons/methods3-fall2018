---
layout: project-page
title: "Mapping Environmental Injustice in Amsterdam"
linkname: mapping-environmental-injustice-in-amsterdam
author: "Claudia Rot"
tagline: "This project combines different environmental and social parameters to create an environmental risk index for the city of Amsterdam. "
location:
    - place: Amsterdam, the Netherlands
project-link:
    - href: https://thenewschool.carto.com/u/rotc931/builder/d8ad3d92-1803-4d36-9ef5-dfd7d1c824da/embed
tags:
    - tag: Environmental justice
    - tag:  Risk assessment
    - tag:  Spatial inequality
thumbnail-path: img/mapping-environmental-injustice-in-amsterdam/DBDK1HY.png
img-folder: ../../img/mapping-environmental-injustice-in-amsterdam/
timestamp: 12/7/2018 21:53:18
---
The Netherlands has a history of tackling environmental problems as issues that can be solved with technological advancement. There is no language to weave intersections with societal issues into the contemporary sustainability practice. To show the possible correlations between disproportionate burdens of environmental hazards and poor communities and communities of colour. I use data that has been made available by the Dutch government and the city of Amsterdam. Using Amsterdam as my focus area, I combined different environmental hazards and social parameters to create an environmental risk index. 

This project can be used as a tool to start examining to cumulative impact of different environmental stressors in combination with sociodemographic stressors. This examination can be executed by local communities, activists, and policymakers to start looking into what a practice of environmental justice in a Dutch context could look like. This project could also be used as a tool to pinpoint neighbourhoods with a high risk index as focus areas for environmental improvements, rather than neighbourhoods with the highest income or highest popularity with tourists, which is what often happens now. 

![]({{ page.img-folder }}rdnPxB3.png)

Amsterdam is the capital of the Netherlands, situated in the west of the country with a population of almost 850,000. This land use map shows how the city is highly residential. Most of the city’s industry is located in ‘Westpoort’, the city’s port, which is connected to a channel which emerges into the North Sea. Therefore, Amsterdam has a direct connection with the ocean towards the west, but also with the biggest lake of the Netherlands, the IJsselmeer, to the east. Amsterdam was built on marshland, like most of the Netherlands, giving the city a very low elevation. Some parts of the city are built on land that was reclaimed from lakes. These parts are mostly residential neighbourhoods. 

![]({{ page.img-folder }}MjDolMM.png)

When you look at an elevation map of the city, these former lakes become visible again. Big chunks of the city lie below sea level. These areas include the Haarlemmermeer, now Schiphol airport; a neighbourhood in the Oost borough, called the Watergraafsmeer; and a part of the Noord borough, called the Buikslotermeer. The last part of each of these neighbourhood’s names ‘meer’ is the Dutch word for lake, and directly refers to the name of the lakes that used to be there. 

The low elevation of Amsterdam brings us to the first, and biggest environmental risk the city has to deal with; flood risk. For the environmental risk index I wanted to include as many environmental parameters as possible. For the scope of this project, I included the following parameters: Elevation, noise pollution (highways, airport, and railroads), air pollution (PM10, PM2.5), and proximity to industrial sites (with buffers of 300, 600, and 1000 meters having different risk levels). For the social parameters I included the house sales price per square meter for 2017 and the population percentage of people with a non-western migration background. 

![]({{ page.img-folder }}lrDA7EY.png)

I created the resulting map by conducting a raster analysis. After acquiring each layer and clipping it to my desired extent, I had to make sure that each layer was a raster. Next, I had to normalize the values for each layer. By doing this I could do calculations with each layer and have them count equally. However, I decided to make the flood risk (elevation) count double because it is the biggest risk for the city. After normalizing all values I used the following formula in the raster calculator to create the risk index map:

PM2.5 + PM10 + NoisePollution + Industry - RealEstateValue - Elevation 

![]({{ page.img-folder }}ANVbMqR.png)

By adding some geographical context, such as the borders of the different boroughs, the biggest streets, building footprints, and the locations of most urban green spaces I made the map more comprehensible. 

![]({{ page.img-folder }}lfgFPn9.gif)

This map animation compares the environmental risk index to the locations of communities with a high percentage of people with a non-western migration background. Whereas people with a non-western migration background do not always seem to live in neighbourhoods with a high risk index, one can clearly see that the areas with the lowest risk index are mostly not populated by people with a non-western migration background. 

In addition to flood risk, the biggest social risk right now can be argued to be housing affordability. The last few years have been marked by a growing housing crisis in Amsterdam. The city does not have a lot of room for expansion, and is stuck with a dilemma of either building new housing in contested green spaces, or demolishing existing buildings to replace it with higher-density housing. The inability of different city governments to make these big decisions has led to a housing shortage and rapid gentrification. This has resulted in incredibly high rents on the private market and very high prices for houses that are for sale. The map animation below shows the decrease and increase in the paid price per square meter after the start of the financial crisis in 2008 up to 2017. 

<blockquote class="imgur-embed-pub" lang="en" data-id="PnTnqvn"><a href="//imgur.com/PnTnqvn"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

Finally, I wanted to make all the social and environmental parameters more interactive and easier to distinguish from each other by compiling the different layers in Carto. 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/rotc931/builder/d8ad3d92-1803-4d36-9ef5-dfd7d1c824da/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Right now, the map allows users to compare at noise pollution data, industrial site data, and real estate value. Instead of displaying every layer directly on the map, I chose to only use the real estate data in a widget. Working with shapefiles that cover almost the entire map can make the map difficult to read, but I tweaked the opacity values of the noise pollution polygons to decrease when the user zooms in on an area. I would like to add the risk index map to the carto map so that users can zoom in on area to see what the risk index is in their places of interest. However, I have not been able to upload raster files into a Carto map within the scope of this project. 

For future expansion of this project I would like to create a more interactive and deepened version of the risk index. I would like to include more environmental and social risks within the index. Furthermore, it would be interesting to argue why different risks could have different weights in the risk formula. Doing case studies for different cities in the Netherlands, or the country as a whole, would also be a good expansion of the project. 
