---
layout: project-page
title: "Re-Mapping Resilience"
linkname: re-mapping-resilience
author: "Abby Zan"
tagline: "Re-mapping resilience using modeling, Georeferencing, and a proposal for subjective story-based mapping."
location:
    - place: Washington, D.C.
project-link:
    - href: https://thenewschool.carto.com/u/schwa464/builder/a7344a44-3636-4821-b5ea-53ff7c99bc24/embed
tags:
    - tag: resilience, displacement, fear, care
thumbnail-path: img/re-mapping-resilience/Pa4p9vc.png
img-folder: ../../img/re-mapping-resilience/
timestamp: 12/7/2018 14:59:25
---
In 2016, Washington, D.C. was selected to be part of the 100 Resilient Cities program, marking the start of a rapid increase in attention and resources to the District in the arena of urban resilience. Resilience has risen to prominence as a global urban development paradigm, seen by many as the successor of the sustainable development paradigm. In resilience and other comprehensive planning and private development schemes, the neighborhood of Anacostia and surrounding Ward 8 have been in the spotlight as a prime target both for resilience efforts and for new development and real estate investment. While resilience is framed as objective and beneficial for communities, this project seeks to better understand how resilience policies will impact the community of Anacostia, and challenge the existing (problematic) interpretations and representations of resilience in D.C. At the core of the project are three central questions:

What are the geographies of climate justice in Washington, D.C.?
How can alternative mapping methods challenge dominant ideas about resilience planning in D.C.?
How can mapping be used as a tool to elevate the voices of residents in areas like Anacostia which are most directly impacted by resilience planning and threats of displacement? 

Existing publicly available resilience maps in Washington, D.C. are scarce, unclear, and, my hunch was, oversimplified the terrain of resilience in the District. They draw a (false) binary between social and physical infrastructure, use areas so large as to be un-meaningful (wards, which each have around 75,000 residents), and are designed in an unclear way, that makes it difficult to see how different factors of resilience relate to one another. Finally, these maps also lack any temporality: ignoring the histories that produced the geography of resilience and vulnerability, as well as the possible futures that await communities if current patterns of development and displacement persist in the District.

I researched existing indices for resilience, displacement, and other aspects of social/community health in cities. Based on this research and on the indicators of resilience discussed in D.C planning documents, I created a resilience index to model resilience by census tract. The factors included in this model were:

* Median income 
* Very young/old population (under 5 years, over 65 years)
* Health insurance (% uninsured)
* Proximity to storm surge zone (% land area within 200 meters)
* Cooling centers per capita (cooling centers in census tract divided by population)

Below is a choropleth map that demonstrates the range of resilience scores based on these factors:

![]({{ page.img-folder }}u0JstNt.png)

So, how does resilience line up with the priorities of District officials? The map below layers onto the resilience index map some of the priority planning areas (traced from a planning map using Georeferencer GDAL). 

![]({{ page.img-folder }}42cFmkC.png)

One of my major questions was how resilience impacts displacement (and vise versa), so I also created a displacement index map, to begin to analyze the relationship between these two kinds of risk. The factors in the displacement index were:

* Median income
* % Renters (vs. owners)
* Proximity to Business Improvement District (% land area within 100m)
* Proximity to Economic Development Zone (% land area within 100m)

![]({{ page.img-folder }}bKmZslr.png)

While these maps help start to create a picture of city-wide distribution of different forms of risk, they lack the specificity and meaning of more granular maps. I chose the most distinct highest ranking and lowest ranking “clusters” of resilience (both contain three census tracts in the top/bottom five of the index). The following qualitative maps show some of the key land use features and landmarks in these areas of the city. The first cluster is situated the Kalorama/Adams Morgan Neighborhood, an affluent part of town with census tract median household income as high as $104,000, and an 86% white population. This cluster is supposedly also home to the Obamas and the Kushners:

![]({{ page.img-folder }}DXyFDZv.png)

The second cluster (low resilience) is situated in the area of Anacostia/Congress Heights, in Southeast, D.C. The median household income in the tracts in this cluster is as low as $14,692, and 98% of the population identifies as Black. 

![]({{ page.img-folder }}7o4bPyQ.png)

To begin to make sense of the relationships between resilience and displacement, it may be helpful to look at the top 10 and bottom 10 ranking census tracts for each model in relation to one another:

![]({{ page.img-folder }}asWJIBL.png)

The top and bottom 10 census tracts highlight areas of interest worth zooming in on, but also may start to paint a picture of the relationship between resilience and displacement risk. Based on these maps, it seems that there is a clear correlation between high displacement risk and low resilience scores. However, high resilience does not line up as clearly with low displacement risk. This may have to do with the fact that the low displacement risk areas (in the far Northwest) are also areas with higher populations of families and elderly people (which factors into lower resilience), as well as areas farther from new development/downtown (which factors into lower displacement risk). There are also more home-owners in Northwest, D.C. than in the more centrally located downtown census tracts with high resilience scores. 

When you layer in race, it is clear that both factors align closely with the distribution of white-identifying residents: resilience and displacement privilege align with white privilege:

![]({{ page.img-folder }}Pi3PfhD.png)

These maps seem to both confirm and to challenge the assumptions of top-down resilience planning Washington, D.C. They confirm some of the notions about where social factors of resilience are less high, but also problematize the spatiality of these factors, as there are pockets of low resilience outside of the two wards designated as highest priority by officials. Also, by pointing out the connection between resilience and displacement, these maps implicate the resilience planning process in the threats to residents’ abilities to remain in their homes and their communities. 

In my Carto map, I include the District’s major revitalization and development plans/zones as layers on top of the resilience and displacement maps, to start to visualize the relationships between existing risks and vulnerability, and current initiatives on the part of the District. These initiatives incentivize new development (commercial and residential), and few protections seem to be in place to keep housing affordable for long-time residents as their neighborhoods gentrify:

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/schwa464/builder/a7344a44-3636-4821-b5ea-53ff7c99bc24/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

These maps complicate the picture of resilience in D.C., but they also replicate that which is problematic about conventional resilience planning: the overgeneralization of big data indicators, the flattening of space and time, and further stigmatizing marginalized communities. They also fail to represent community strength and care, which of course are equally if not more important to any conversation about resilience. By asserting a sort of scientific objectivity, these maps obscure the subjective processes of arriving upon resilience indicators, and the distinct experiences of residents on the ground.

Eventually, I hope to pursue these questions and critiques through oral histories and participatory mapping techniques, to produce a more complete, meaningful, and subjective picture of resilience--particularly in areas like Anacostia which officials are quick to stamp as “vulnerable.” In my theoretical research around resilience, the concepts of fear (fear-based planning, ecologies of fear) and care (care networks, caring economies, care as resistance) arise time and time again.

Short of the first-hand stories and data I would need to produce these kinds of maps, I created an experimental set of subjective maps based on both my own assumptions and insights from the interviews and histories I have gathered so far in my field work. By using data from the user-generated Open Street Maps, these maps approximate (inadequately of course!) the subjectivity of the kind of fear/care/resilience map I would like to eventually produce.

![]({{ page.img-folder }}QJsrwgA.png)

The map below zooms in on these dimensions of fear and care in the low-scoring resilience census cluster shown before:

![]({{ page.img-folder }}aJvk39q.png)

It is difficult to draw major conclusions today about the patterns of fear and care in these highly subjective maps. They perhaps begin to provoke a conversation about the lived experiences of fear and care, and how these experiences and geographies may relate to wider conversations of resilience and displacement underway in D.C.

Based on the one oral history interview I have conducted thus far, I have started to produce a prototype process and online map for an oral history resilience map, Georeferencing .TIFF images made on Fieldpapers.org, and linking to audio clips housed on Soundcloud. This is very much a work in progress at this point, but I look forward to drawing out the personal stories of resilience in D.C. 

![]({{ page.img-folder }}A3JO8pn.png)

