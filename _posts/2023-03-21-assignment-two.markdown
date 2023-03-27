---
layout: post
title:  "Revealing underground pattern of prostitution in San Francisco"
link_color: red
date:   2023-03-21 14:22:33 +0100
categories: jekyll update
---

## Background
Welcome to an investigation of prostitution in San Francisco, created as a part of the course *Social Data Analysis and Visualization* at DTU. Reading this web page, will reveal stories from the San Francisco Crime Data and communicate insights using narrative storytelling and interactive visualizations created using GitHub and Jekyll. Enjoy!

## Introduction
The [**San Francisco crime data set**] [SFdata] is a public available data set that contains information about crime incidents recorded in San Francisco in the period from 2003 to 2018. We will scrutinize on crimes categorized as prostitution, one of the oldest professions of human kind. Various crimes are recorded under this category, for instance  *Disorderly housekeeping, human trafficking and pimping*. In San Francisco  [**prostitution is illegal**][wiki] for both the buyer and the seller, so both crimes related to buying and selling are represented in the data set. Most of the prostitution related crimes takes place in six of the districts in San Francisco, namely Central, Mission, Northern, Southern, Taraval and Tenderloin. These will be the main focus.

## On what weekday are most prostitute related crimes recorded? 
First of, Figure 1 shows the number of prostitution crimes recorded within the six districts. The busiest day of the week is surprisingly, mostly Thursday. Normally, it is said to be Friday, leading to the conclusion that a lot of people in San Francisco enjoy their weekend a bit earlier or it could simply be, that the police in San Francisco enjoys the Friday off. Therefore less people are arrested.
In the districts Southern and Taraval, the contrast of the number of incidents between Thursday and other days is very large. What causes this spike in the count of incidents on Thursdays is unknown. 

<img src="{{site.baseurl}}/assets/images/barplot2.png">

**Figure 1:** Number of incidents recorded on different weekdays in the six districts. Check out our code in our <a href="{{site.baseurl}}/assets/images/Assignment02.html"> **Jupiter Notebook**.</a>

## Where are the hotspots for prostitution in San Francisco?
Figure 2 displays a map over San Francisco where the position of the incidents is marked. In San Francisco there are mainly two hotspots, where the crimes take place. The first one is around Capp Street, that is known as the [**“Red-light district”**][rl] of San Francisco. Capp street is in the Mission district and is the district with most incidents in general. The other hotspot is located across the three districts Northern, Tenderloin and Central. Noticeable, only a very little part of the incidents that takes place outside these two hotspots. 


<embed 
       type="text/html" 
       src="{{site.baseurl}}/assets/images/map.html"
       width="750"
       height="550"
       >


**Figure 2:** Map over San Francisco that shows where the incidents are recorded. Capp Street are marked using a red marker. Curious on how to make interactive maps? Check out our <a href="{{site.baseurl}}/assets/images/Assignment02.html"> **Jupiter Notebook**.</a>

## At what time during the day are most crimes recorded?
The daily pattern of crimes recorded are very different for each districts. In Figure 3 this is visualized using an interactive plot. Feel free to explore the map. It reveals, that in the districts Mission, Northern and Tenderloin, most of the incidents are recorded during the evening and night, whereas the districts Southern and Taraval are busier during the day. Please note, that this information should not be used as a tourist guide, planning a day trip. The consequences can be up to 6 months in jail and a \$1,000 fine - an expensive night out.

For such, a trip to Nevada is recommended. Nevada is the only U.S. state where prostitution is legally permitted in some form.

<embed 
       type="text/html" 
       src="{{site.baseurl}}/assets/images/bokehfigure.html"
       width="750"
       height="550"
       >

**Figure 3:** Interactive plot that shows the hourly patterns in the districts. Click on the squares to hide/show data from a certain district. Find out how to make this interactive visualization on your own in our <a href="{{site.baseurl}}/assets/images/Assignment02.html"> **Jupiter Notebook**.</a>


## To sum up
In this post about prostitution crimes in San Francisco, we revealed three interesting insights from the data: 
* Most prostitution crimes take place on Thursdays.
* There are two hotspots of prostitution in San Francisco – one around Capp Street in Mission and one across the districts Northern, Tenderloin and Central.
* The daily pattern of incidents is very different in the districts. In some districts there are most crimes during the day, while in other districts most crimes are recorded in the nighttime. 



[SFdata]: https://data.sfgov.org/browse?category=Public+Safety
[wiki]: https://en.wikipedia.org/wiki/Prostitution_in_California 
[rl]: https://www.sfchronicle.com/sf/article/sex-workers-capp-street-17774301.php 

