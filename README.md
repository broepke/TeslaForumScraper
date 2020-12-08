# TeslaForumScraper

## Web Scraping the Tesla User Discussion Forums with R
Techniques in this notebook were built off of the learnings from the Data Camp course on Web Scraping with R.  This takes into recommendation from DataCamp the guidance to "Be Kind" to web servers, therefore it includes delays before each scraping call to pages using the `slowly` function from `purrr`.  

## Target Forum
It is currently set up to do the Tesla Model 3 forum based on a date created of December 7th, 2020.  
https://forums.tesla.com/categories/tesla-model-3

## Web Scraping with R from DataCamp
Have you ever come across a website that displays a lot of data such as statistics, product reviews, or prices in a format that’s not data analysis-ready? Often, authorities and other data providers publish their data in neatly formatted tables. However, not all of these sites include a download button, but don’t despair. In this course, you’ll learn how to efficiently collect and download data from any website using R. You'll learn how to automate the scraping and parsing of Wikipedia using the rvest and httr packages. Through hands-on exercises, you’ll also expand your understanding of HTML and CSS, the building blocks of web pages, as you make your data harvesting workflows less error-prone and more efficient.

https://learn.datacamp.com/courses/web-scraping-in-r
