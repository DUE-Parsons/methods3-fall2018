---
layout: project-page
title: "Mapping Gentrification Risk in the Grand Paris"
linkname: mapping-gentrification-risk-in-the-grand-paris
author: "Manon Vergerio"
tagline: "This project analyzes gentrification risks around Paris associated with the 2024 Olympics and the new transit network under construction. "
location:
    - place: Paris, France
project-link:
    - href: https://thenewschool.carto.com/u/manonvergerio/builder/190118c2-f145-4924-8e4d-1e65f8067ba4/embed
    - href:  https://thenewschool.carto.com/u/manonvergerio/builder/d59844ad-17af-4884-bef1-3ba271150a05/embed
    - href:  https://thenewschool.carto.com/u/manonvergerio/builder/a4dff21d-c0ad-4e0d-8a0c-8903f39340d0/embed
tags:
    - tag: Housing justice
    - tag:  infrastructure
    - tag:  gentrification
thumbnail-path: img/mapping-gentrification-risk-in-the-grand-paris/IfL2SFR.jpg
img-folder: ../../img/mapping-gentrification-risk-in-the-grand-paris/
timestamp: 12/6/2018 20:04:15
---
The Paris 2024 Olympics are being touted as an exceptional opportunity to accelerate the construction of the Grand Paris Express subway network, a 38 billion euro transit project that will undeniably transform the geography of the Paris metropolitan area. Public officials claim that these infrastructure projects will channel investments into under-resourced suburban territories, in particular the northeastern suburb known as Seine-Saint-Denis. However, given the increasing unaffordability of housing in Paris, many residents and activists on-the-ground view the Grand Paris and the Olympics as a vehicle to precipitate processes of gentrification and population displacement. I decided to map current demographics and assess gentrification risks to investigate these contradictory claims, and to question the glossy rhetoric surrounding the Grand Paris and the 2024 Olympics.

![]({{ page.img-folder }}gFPJHYS.jpg) 

![]({{ page.img-folder }}IS08i5J.jpg) 

To contextualize my analysis, it is important to note that there is a long history of fragmentation between Paris and its surrounding suburbs, known as banlieues. Historically, this duality was produced by urban renewal plans and policies that expelled the working class from the heart of Paris to its periphery. This deep disconnect between Paris and its suburbs is important to consider because the Grand Paris and the 2024 Olympics are being marketed as an opportunity to stitch this fragmented territory back together. I wanted to start my spatial investigation by mapping current demographics, to examine how the Parisian metropolitan space is organized and segregated along class and racial lines. These parameters are important to consider when mapping gentrification, since low-income communities of color tend to be more at risk. Since the French State does not collect data about race and ethnicity, I used immigration and foreign-born populations as indicators instead. I decided to focus on the first ring of suburbs around Paris - la Petite Couronne (The First Crown) - because it is more at risk of gentrification due to its proximity to the city than outer suburbs.

![]({{ page.img-folder }}H2wQA0G.jpg) 

As I suspected based on the historical processes aforementioned, the residents of the city of Paris are primarily white-collar workers, and few are immigrants or foreign-born. In contrast, the suburbs, in particular the northeastern suburb of Seine-Saint-Denis, are primarily working class, with a high proportion of immigrants and foreign-born residents. 

Having gotten a sense of demographics, I wanted to layer three major urban processes reshaping the Paris metropolitan area, as these frequently came up in my interviews with residents and public players and in my secondary source research. These include the new transit lines and stations being constructed as part of the Grand Paris Express network, the 2024 Olympic sites, as well as urban renewal areas, where public housing complexes are being redeveloped into mixed-income neighborhoods through the National Urban Renewal Program (Programme Nationale de Rénovation Urbaine). I focused my map on Seine-Saint-Denis, the northeastern suburb where a cluster of Olympic sites are being sited. Seine-Saint-Denis is also known as “the 93”, which is its administrative departemental number. 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/manonvergerio/builder/190118c2-f145-4924-8e4d-1e65f8067ba4/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe> 

Seeing these distinct processes layered in space raises questions on how the Grand Paris and the 2024 Olympics will ensure that these new infrastructure projects will benefit long-time residents, since many live in public housing complexes faced with urban renewal and are not guaranteed being relocated on-site. Of the 68 new transit station districts being built as part of the Grand Paris, 42 contain a neighborhood undergoing urban renewal. One of my interviewees described this urban renewal process as a “steamroller” tearing through the suburbs and displacing low-income residents. 

Given the processes underway, I wanted to build a model that could predict gentrification around Paris, with the hope that it might be useful for residents and activists organizing against displacement. To develop my model, I looked into the indicators used by different cities that have developed early warning systems for gentrification and displacement. I selected median income and proximity to future transit stations as my two indicators. My model could be rendered more complex by using additional indicators such as changes in property values, but I had difficulty accessing real estate data in France. 

The first indicator I used is median income. In my model, low-income census tracts are more at risk of gentrification than high-income census tracts. Neighborhoods that are already affluent (i.e. most of the City of Paris), are not going to be gentrified, while low-income residents run the risk of being displaced as property values increase in their neighborhoods. 

![]({{ page.img-folder }}0h4Ha0m.jpg) 

The second indicator I used is the proximity to future Grand Paris Express transit stations, the largest transit development project in Europe, which will add five new subway lines and 62 new transit stations to the Paris metropolitan area. When new transit lines are constructed, property values tend to increase around new transit stations, due to increased attractivity. The Grand Paris Express will connect formerly isolated suburbs to the heart of Paris with a high-speed subway network. Based on my research through media articles and real estate reports, neighborhoods that were previously seen as undesirable are already gaining new attractivity due to the Grand Paris Express train. 

 ![]({{ page.img-folder }}GK3xOJx.jpg) 

I aggregated the two indicators to create a “Gentrification Risk” model. I also highlight a “hotspot” in the City of Saint-Denis, a low-income suburb on the edge of Paris where many Olympic sites are going to be located. Based on my interviews and research, Saint-Denis has been described as the “eye of the storm” of the incoming gentrification wave, due to its proximity to Paris and gentrifying communities of Saint-Ouen and Pantin, new transit stations, and the location of several Olympic sites.  The Grand Paris Express train stations in Saint-Denis are set to be completed by the 2024 Olympics to facilitate the circulation of tourists and athletes throughout the metropolitan space. 

 ![]({{ page.img-folder }}IfL2SFR.jpg) 

I then brought my map into Carto to make it interactive and public-facing. Users can click layers on and off to explore different indicators in the Gentrification Risk model. My concern is if my map falls into the wrong hands (ex: real estate investors), so for now the map is not fully public.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/manonvergerio/builder/d59844ad-17af-4884-bef1-3ba271150a05/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

My intention in mapping gentrification risks is not to make residents feel defeated, but rather to provide an early warning system that can bolster activism. Urban space is produced not only by top-down State policies, real estate developers, and construction companies, but by those who inhabit the space everyday and develop resistance strategies to claim their right to the city. My final map, which is in prototype form, is my attempt to catalogue the current residents and activists organizations mobilizing against the Grand Paris and its various ramifications (ex: 2024 Olympics, public housing demolition). After interviewing some activists organizing against the Grand Paris and the Olympics, I learned that current struggles tend to be siloed and dispersed throughout the Paris metropolitan space, and that several of them are trying to build a stronger coalition that would bring these various grassroots organizations into a cohesive force against the Grand Paris. One of the tools they hope to use to strengthen their coalition-building efforts is a unifying map visualizing the various sites of resistance. Since this is part of my technical skills, I developed this prototype to share with them on my next trip to Paris as something I could contribute to their organizing campaign. In this map, I layered my “Gentrification Risk” map with active sites of resistance. In addition to showing sites of contestation, I want to couple this spatial show of force with stories from activists, to build a multivocal collection of resistance stories and strategies. My hope is to not only record audio and video stories during my next trip, but to allow people to upload their own stories to the platform, using a crowdsourced format. 

![]({{ page.img-folder }}OSUWxcb.jpg)
