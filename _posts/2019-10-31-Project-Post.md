---
layout: post
title: Brewery Statistics Blog Post
date: 2019-10-31
---

The Project

I was recently working on a web scraping porjecto to find statistics on craft brewing across the US. 

TO do this I found information from the  Brewer's Asoocaition website.  I was looking for data broken up by state to compare factors such as total production, economic impact on the state, number of breweries as well as prouction and number of breweries per capita.

I also scraped information from the Beer Institute about general levels of beer consumption per capita per state.  I wanted to compare these numbers to the statistics about craft breweries.

The goal of this project was to test out my web scraping skills and to see if there were any interesting trends that I could identify around the craft brewing inudstry in the US and beer drinking habits in the US.



Difficulties

In the course of looking for data for this project I discovered that brewing and drinking statistics can be difficult to find, particularly in a format that is condusive to straight forward web scraping.  
Some examples include entire pages that are one class with the statisics all bunched together in one long string, or as a table that doens't separate individual cells in the html.  
Another problem I found included finding well organized information that wasn't able to be scraped due to the permissions of the site it was on.



The Process

The way the statistics were presented on the  Brewer's Assocation website presented an interesting siutaion. 
All of the stats were in cells for each state, which can be seen below:

![Image](https://github.com/dramsay801/dramsay801.github.io/blob/master/images/Capture.PNG)


I initially thought to grab all of the statistics for each state by going thorugh a loop and pulling out the values from each cell.
However I found that I could grab all of one type of value from each cell on the page. So I instead scraped each statistic I was looking for
from all 50 State and DC one statistic at a time.

I then had to convert all of the stats into numeric form as they were all initially scraped as characters. 

Next I scraped the consumption stats from each state and combined the resulting dataframe with my initial one to put all of my data in the same place.


The Findings

This section will be a little sparse for now, but will be updated as I go back and conduct more comprehensive analysis on my data.

To begin, let's go over some big picture, national level descrpitive analytics.

The total economic impact of the craft brewing industry in 2018 was about $79 billion.  Which boils down to about $241.65 spent (only on craft beer) per person in the US in one year.

