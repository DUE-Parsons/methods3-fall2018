---
layout: project-page
title: "Towards a Natural Gas free Amsterdam"
linkname: towards-a-natural-gas-free-amsterdam
author: "Daniel Bieckmann"
tagline: "An evaluation of the shift away from natural gas in Amsterdam, focusing on transition difficulty and available renewable energy infrastructures."
location:
    - place: Amsterdam, The Netherlands
project-link:
    - href: https://thenewschool.carto.com/u/danielbieckmann/builder/1b037144-05fd-4d32-a2fd-4f8195d6d9fe/embed
tags:
    - tag: energy transition
    - tag:  renewable energy
    - tag:  Amsterdam
    - tag:  Energy Infrastructure
thumbnail-path: img/towards-a-natural-gas-free-amsterdam/I0SfIVA.jpg
img-folder: ../../img/towards-a-natural-gas-free-amsterdam/
timestamp: 12/4/2018 9:32:41
---
![]({{ page.img-folder }}m8b7JAA.jpg)

The municipality of Amsterdam (The Netherlands) has taken up the challenge to move to a natural gas free city by 2040. This effort requires a drastic restructuring of the energy systems throughout the city to compensate for the energy currently generated from natural gas. This project aims to provide an overview of these alternative energy infrastructures present in the city, as well as identify which neighborhoods might provide the biggest challenges in transitioning away from natural gas.

The following map presents the chosen format to represent most of the found data- the neighborhood level. Representing the different data sources at this scale allows for comparison between different parts of the city, while keeping some oversight on the city as a whole. 

![]({{ page.img-folder }}nOBhMm5.jpg)

Firstly, this following interactive map gives us some context on some of the major available energy infrastructure in the city of Amsterdam. Specifically it aims to provide an insight in current renewable energy infrastructures that can serve as a starting point to move away from the natural gas consumption, by focusing on areas wind energy generation, solar energy, and thermal energy systems. 

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/danielbieckmann/builder/1b037144-05fd-4d32-a2fd-4f8195d6d9fe/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

In order for us to construct a map to identify areas that might face more difficulty in transitioning away from natural, three variables were chosen. Firstly, the state of the existing infrastructure and its compatibility with natural gas or alternative energy systems was evaluated. The following map was created representing the fraction of buildings per neighborhood that was constructed between 1960 and 2016- these buildings tend to have stronger natural-gas oriented infrastructure, and might thus provide more difficulty in transitioning to alternative energy sources. As could be expected, these buildings are mostly in the outer, newer rings of the city.

![]({{ page.img-folder }}mT1LeFn.jpg)

Secondly, the amount of natural gas consumed per neighborhood was evaluated, assuming that those areas that currently use larger amounts of natural gas will need more extensive alternative energy sources and infrastructures to compensate. The following map shows the amount of gas (in m3) consumed per surface area (m2) for each neighborhood.

![]({{ page.img-folder }}dPM3Ui2.jpg)

Lastly, this transition model takes into account the average house worth of the different neighborhoods. The municipality of Amsterdam- in cooperation with private energy providers NUON and Liander- provides some support to transition through transition subsidies (such as through the NOMO – zero on the meter fund); information, and by privatizing some of the construction of the needed energy infrastructure. Still, the transitions away from natural gas depend heavily on individuals plans and efforts to change the infrastructure of their house or complex. Thus, the economic situation of different neighborhoods seems a relevant factor in evaluating the challenge of transitioning away from natural gas. In the absence of relevant spatial data on income, house worth is used as an indicator based on the following assumption- although this differs per individual, overall individuals with more expensive houses tend to have higher incomes, and are thus expected to experience less economic difficulty in transitioning away from natural gas. The following map shows the mean house price per neighborhood.

![]({{ page.img-folder }}b8Bvdv4.jpg)

To create a map representing the relative difficulty to transition away from natural gas for the different neighborhoods in Amsterdam,  the three above-mentioned indicators (building age; natural gas consumption; house worth) were normalized on a scale from 0-1 each, in which 1 represented the most difficulty to transition away from natural gas for that indicator compared to the other neighborhoods. This resulted in the following map, in which all three indicators are assumed to have an equal weight in deciding the relative transition difficulty.

RELATIVE TRANSITION DIFFICULTY (EQUAL WEIGHT):
![]({{ page.img-folder }}3ehojPG.jpg)

However, one indicator might turn out to be a more deciding factor than others in determining the difficulty to transition away from natural gas in a certain neighborhood. The following maps represent the relative transition difficulty per neighborhood, with a specific focus on one of the three indicators.

RELATIVE TRANSITION DIFFICULTY (FOCUS ON BUILDING AGE):
![]({{ page.img-folder }}0gEz8lY.jpg)

RELATIVE TRANSITION DIFFICULTY (FOCUS ON GAS CONSUMPTION):
![]({{ page.img-folder }}aE4KVTY.jpg)

RELATIVE TRANSITION DIFFICULTY (FOCUS ON HOUSE WORTH):
![]({{ page.img-folder }}7ZQqcgq.jpg)

Although an emphasis on the different indicators leads to strongly different maps, most of the maps show that the neighborhoods in the West of Amsterdam provide a larger challenge in transitioning away from natural gas. Currently no programs exist that aid in the transition in those areas specifically- perhaps as the path of transitioning away from natural gas continues more attention needs to be paid to these neighborhoods.
