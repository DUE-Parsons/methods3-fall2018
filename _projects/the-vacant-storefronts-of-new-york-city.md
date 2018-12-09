---
layout: project-page
title: "The Vacant Storefronts of New York City"
linkname: the-vacant-storefronts-of-new-york-city
author: "Rosella Soravia"
tagline: "This mapping project concerns itself with the phenomena of shuttered storefronts in New York City demonstrating its causes and effects."
location:
    - place: New York, NY, USA
project-link:
    - href: https://thenewschool.carto.com/u/sorar852/builder/9f5c5927-12e8-4198-acf9-e96e5c0be5a6/embed
    - href:  https://imgur.com/a/Mf7tLst
    - href:  https://imgur.com/a/m9fOYdv
    - href:  https://thenewschool.carto.com/u/sorar852/builder/0034a5c2-33c0-4032-b4d5-5c9921c55087/embed  
tags:
    - tag: increasing rent
    - tag:  commercial leases
    - tag:  real estate
    - tag:  chain stores
    - tag:  displacement
    - tag:  local establishments
    - tag:  diminishing bookstores
thumbnail-path: img/the-vacant-storefronts-of-new-york-city/TaBjGAk.png
img-folder: ../../img/the-vacant-storefronts-of-new-york-city/
timestamp: 12/5/2018 18:30:29
---

The New York City streetscape has been transformed, not only visually but also economically. This can be seen by the staggering numbers of vacant storefronts dotting its most popular retail corridors. Several studies indicate that 20 percent of Manhattans storefronts lie vacant where commercial rents have soared. This is provoking a battle of survival in the current real estate market of NYC. 

![]({{ page.img-folder }}MQA3hrs.jpg) 

The median rent maps show how residential rents have been significantly increasing over the past years in Manhattan. This phenomena is called “high-rent blight” and is slowly moving into the other boroughs of New York City. In the past years, there have been several debates over how to stop it and how to regulate rent negotiations between small businesses and landlords when leases come up for renewal. I downloaded the data from StreetEasy but unfortunately I had a hard time finding data on commercial median rent, and therefore commended with the residential data. This rent data was categorized by Neighbourhood which presented a struggle as these are not administrative boundaries that are outlined according to the same principles. Therefore I modified the two excel sheets in correspondence to one another. I had to be precise and pay attention to which neighborhoods overlap. After, I joined the datasets and used the styling graduate natural break command to style my map. 

![]({{ page.img-folder }}xEidc1s.jpg) 

Moreover, to demonstrate that residential rent data is an authoritative replacement for commercial rent, the bar graph represents the rise in commercial rent in Manhattan.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/sorar852/builder/9f5c5927-12e8-4198-acf9-e96e5c0be5a6/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Real Estate MAP/s (CARTO)

Landlords and real estate groups are contributing significantly to this phenomena. While landlords that just own one or two building certainly might experience financial hardship from vacant stores, a lot of buildings in New York City are owned by wealthy, diversified landlords or large companies who are less impacted by retaining one vacant store. Small business owners repeatedly mentioned the power the real estate industry possess in the city, as tax benefits and other policies are set in place to strengthen the industry at the expense of the community character. I downloaded the “Active construction projects” data from NYC.gov. This map has only been released in the past year and has been updated ever since. It includes very valuable data about all the new construction sites which are currently happening in New York. On this online CARTO map, a general idea of the different construction sizes is given by colour and circle size. Moreover by clicking on the pop-up, more detailed information like the estimated projects cost, adresse and proposed occupancy is given. 

![]({{ page.img-folder }}WT6oy6P.png) 

Pluto Map

Despite that, I felt that the information had to be illustrated in more detail to portray a sharpened image to the audience. Therefor I turned the CSV into points in order for me to change it into a shapefile. I then used the coordinated column to join it to the Pluto Map using a spatial join. I then styled the map according to the site's square footage using the graduated styling option.  As a result, it is noticeable what scale these projects possess.

![]({{ page.img-folder }}RILXm4H.png) 

Chain Store Map

Over the decade, a thousands of small retailers have closed and been replaced by national chains. As landlords increase the rent, local shops that have been in the area for decades can no longer afford the rent and are being forced out. The only businesses which can provide these high rents are national chain stores like Dunkin Donuts, Subway, Duane Reade etc. Although this has been changing recently, as the “State of the Chains Report” records; food establishments continue to show strong growth, retailers that compete most directly with online outlets- such as shoe and electronics stores, have experienced significant contractions. Overall, a fifth of all national retailers in the city closed stores in the past year, and only one in seven retailers on our list increased their footprint.” The Map shows that the number of Chain Stores has been decreasing in certain borrows through the past years possible due to rising rents. 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/sorar852/builder/0034a5c2-33c0-4032-b4d5-5c9921c55087/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Bookstore Map

Increasing rents also had significant impacts on the character of the neighborhood. Local residents articulated their sadness and frustration over the loss of local businesses as it is burdening the community by extracting social costs.To demonstrate the impact visually I chose to focus on bookstores as these are known as local shops which have been existing for decades and are often run by local residence. I downloaded the data from a Newspaper article using the developer tools. It was published in “the Gotham”  and shows how bookstores have been disappearing from 1970 to 2014 throughout Manhattan. Thus demonstrating the different elements that are causing Vacant Manhattan: the power of Real estate, High Rents & E- Commerce. With the help of the animation styling tool in CARTO I managed to represent the data as a ever moving timeline of disappearing bookstores.  

![]({{ page.img-folder }}UaJY69a.jpg)

Last but not least, the Bar Graph indicates the growing competition from the E-Commerce players that adds to the unprecedented high levels of vacancy across the City.
