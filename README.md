# Powerpage Web Crawler

``Powerpage Web Crawler`` is portable lightweight web crawler using [**Powerpage**](https://github.com/casualwriter/powerpage). 
 
It is a simple html/js application demonstrating developing application using [Powerpage](https://github.com/casualwriter/powerpage). 

![](powerpage-web-crawler.jpg)

## Installation & Run

* No installation is needed, Just download and run ``powerpage.exe``.
* The package is same as [Powerpage](https://github.com/casualwriter/powerpage), only ``powerpage.ini`` is revised.

## User Guide

### Test Crawling

* Input the base url first.
* Click [Crawl Once] to crawl the base page 
* find out the pattent of index page
* find out the pattent of content page
* open Chrome and goto content page, find out the css selector for crawling content

### Start carwling

* click [Crawl Once] to crawl base url once
* click [Crawl All] to crawl all index pages
* double-click on the list of content page, will crawl content of this page, and show in right-panel
* may continue finetune the content definition, then double-click to preview. 

### Sample Sites

* click [Load Sites] to show the list of sample sites.
* click on the site to load the definition, double-click to start [Crawl Once]
* click [Save Site] to save the definition to sample.mdb

## Source Code

It is single html/js program ([pp-web-crawler.html](source/pp-web-crawler.html)) about 200 lines. 

## Modification History

* 2021/06/28, v0.30, first version.
* 2021/07/02, v0.35, add sample sites.


## License

MIT
