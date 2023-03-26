---
layout: post
title:  "Narrative data visulization of the San Francisco Crime Data Set"
date:   2023-03-21 14:22:33 +0100
categories: jekyll update
---

## Background
This post is created as a part of the course ***Social Data Analysis and Visualization*** at DTU. In this post our aim is to reveal stories from the San Francisco Crime Data and communicate our insights using narrative storytelling and interactive visualizations on this web page created using GitHub and Jekyll. 

## Introduction
The [San Francisco crime data set] [SFdata] is a public available data set that contains information about crime incidents recorded in San Francisco in the period from 2003 to 2018. In this post we will focus on crimes categorized as prostitution. Various crimes are recorded under this category, for instance  ***Disorderly housekeeping, human trafficking and pimping***. In San Francisco  [prostitution is illegal][wiki] for both the buyer and the seller, so both crimes related to buying and selling are represented in the data set. Most of the prostitution related crimes takes place in six of the districts in San Francisco, namely Central, Mission, Northern, Southern, Taraval and Tenderloin. In this post we will mainly focus on those districts. 

## On what weekday are most prostitute related crimes recorded? 
Figure 1 shows the number of prostitution crimes recorded in the six districts. In most districts the busiest day of the week is Thursday. In the districts Southern and Taraval, the contrast of the number of incidents between Thursday and other days is very large. What causes this spike in the count of incidents on Thursdays is unknown.


<img src="{{site.baseurl}}/assets/images/barplot2.png">

**Figure 1:** Number of incidents recorded on different weekdays in the six districts.

## Where in San Francisco does the prostitution crime takes place?
Figure 2 shows a map over San Francisco where the position of the incidents is marked. In San Francisco there are mainly two hotspots where the crimes take place. The first one is around Capp Street that is known as the [“Red-light district”][rl] of San Francisco. Capp street is in the Mission district and is the district with most incidents in general. The other hotspot is located across the three districts Northern, Tenderloin and Central. It is a very little part of the incidents that takes place outside these two hotspots.


<embed 
       type="text/html" 
       src="{{site.baseurl}}/assets/images/map.html"
       width="750"
       height="550"
       >
</embed>

**Figure 2:** Map over San Francisco that shows where the incidents are recorded. Capp Strett are marked using a red marker. 

## At what time during the day are most crimes recorded?
The daily pattern of crimes recorded are very different for the different districts. In Figure 3 this is visualized using an interactive plot, where you can click to both show and hide data from different districts. The visualization reveals that in the districts Mission, Northern and Tenderloin, most of the incidents are recorded during the evening and night, whereas the districts Southern and Taraval are busier during the day. 

<embed 
       type="text/html" 
       src="{{site.baseurl}}/assets/images/bokehfigure.html"
       width="750"
       height="550"
       >
</embed>

**Figure 3:** Interactive plot that shows the hourly patterns in the districts. Click on the squares to hide/show data from a certain district.

## Conclusion
In this post about prostitution crimes in San Francisco, we revealed three interesting insights from the data: 
* Most prostitution crimes take place on Thursdays.
* There are two hotspots of prostitution in San Francisco – one around Capp Street in Mission and one across the districts Northern, Tenderloin and Central.
* The daily pattern of incidents is very different in the districts. In some districts there are most crimes during the day, while in other districts most crimes are recorded in the nighttime. 


[SFdata]: https://data.sfgov.org/browse?category=Public+Safety
[wiki]: https://en.wikipedia.org/wiki/Prostitution_in_California 
[rl]: https://www.sfchronicle.com/sf/article/sex-workers-capp-street-17774301.php 

