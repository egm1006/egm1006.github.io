---
layout: post
title: "Nokia Webscraping Project"
date: 2019-22-08
---

Recently, I created a project using R Studio in order to get some experience with webscrapping. I chose to scrape information from
a Wikapedia page that contained data on various Nokia Phone products. There were numerous different data tables which ranged in 
the number of columns but all contained information such as the name of the phone model, camera data, release year, technology, 
screen type and generation. The link to the Wikapedia page is listed below:
https://en.wikipedia.org/wiki/List_of_Nokia_products

The Purposed of this project was to extract data from the internet regarding Nokia phone models and create a code that analysed 
the different features of the models and and saw how they changed as the years progressed, with an emphasis on the camera quality
and specifications.

In total, 12 different tables were extracted from the webpage and put into R Studio. These tables were then cleaned and the number
of column features were reduced so each table had the same column dimensions and information. Next, the 12 tables were combined into
one master data frame. This data frame was then used to plot various features into a number of different graphs. One of my favorite 
graphs was a histogram showing the change in camera specifications over the years based upon models. An Image of this graph is shown
below:

!(Image){https://github.com/egm1006.github.io/blob/master/Images/Nokia%20Cameras.png)

In addition to the original Wikapedia web scraping, finacial data was also scrapped from the web which had Nokia's stock value 
over
the years contained in a table. This table contained the opening, closing, high and low stock value for each year. This data was 
then processed using the QuantLib package in R Studio and was attempted to be plotted in a candlestick graph, showing all the 
finace
data columns over the given years. This was done to look at how the number of models released in each year along with the 
technical
specifications effected the companies stock prices. A view of Nokies stock value is shown in the graphic below:

!(Image){https://github.com/egm1006.github.io/blob/master/Images/Nokia%20Stocks%20Prices.png)

This was a really exciting project to work on and a great introduction to the power of web scraping along with good experience in 
using R Studio to make what initially seems to be a dry subject into captivating graphics!

The results of this project have also made me want to discover more about the QuanLib library in R. I look forward to seeing where
this library will lead me next!
