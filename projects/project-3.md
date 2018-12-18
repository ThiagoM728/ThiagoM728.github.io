---
layout: project
type: project
image: images/webscraper.jpg
title: IMDB Web Scraper
permalink: projects/IMDB Web Scraper
# All dates must be YYYY-MM-DD format!
date: 2018-10-12
labels:
  - Python
  - GitHub
  - Frameworks
summary: A IMDB web scraping program.
---

<img class="ui image" src="{{ site.baseurl }}/images/webscraper2.png">

  As an internet of things enthusiast the topic of web scraping was introduced to me at one of my universities (FAU) hackaton’s, that weekend I sought to try to implement my own web scraping script. My language of choice was Python since there are some great libraries such as urllib to help me get started. Next step was finding the target, so IMDB was chosen simply because they have a rich library and standard format for most of the search results.

  My intent was to make a standard template that could be modular enough to easily change scraping targets and scripts while keeping the framework intact. An open source framework (Scrapy) was chosen for simplicity while deploying multiple apps. This app will scrape for data related to the current top 250 movies in IMDB’s library and save the results to a .JSON file once a request is made. My experience building this app has being insightful and has made me appreciate the possibilities this method has to offer while working on my next projects.


The source code is available at [Github](https://github.com/ThiagoM728/IMDBwebscraper).

