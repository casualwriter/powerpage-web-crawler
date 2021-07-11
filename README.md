# Powerpage Web Crawler

``Powerpage Web Crawler`` is portable lightweight web crawler using [**Powerpage**](https://github.com/casualwriter/powerpage). 
 
It is a simple html/js application demonstrating developing application using [Powerpage](https://github.com/casualwriter/powerpage). 

Powerpage Web Crawler (v0.50) is powerful and easy-to-use web scrawler suitable for blog site crawling and offline-reading. 

Just simply define below

* base-url := the home page of favor blog site
* index-pattern := RegExp of the url pattern of category page
* page-pattern := RegExp of the url pattern of category page
* content-css := css selector for blog content 

Program will
 
* crawl all index page.
* find out all url of content pages. 
* crawl content fro one page, or all pages. 
* save setting and links ato database (support multiple sites)
* save content pages to local files.
* off-line reading from local files.
 
![](powerpage-web-crawler.jpg)

## Installation & Run

* No installation is needed, Just download and run ``powerpage.exe``.
* The package is same as [Powerpage](https://github.com/casualwriter/powerpage), only ``powerpage.ini`` is revised.

## User Guide

#### Test Crawling

* Input the base url first.
* Click [Crawl Once] to crawl the base page 
* find out the pattent of index page (regexp)
* find out the pattent of content page (regexp)
* open Chrome and goto content page, find out the css selector for crawling content

#### Start carwling

* Click [Crawl Once] to crawl base url once.
* Click [Crawl Max] to crawl all index pages (depends on max-page setting).
* Click [Stop] to stop crawling process.
* Double-click on the list of content page, will crawl content of this page, and show in right-panel.
* Single-Click on the list of content page, will show page from local file (if saved) 
* May continue finetune the "content" definition, then double-click to crawl the content page.
* In right-panel, click on [Save To File] will save crawl page to html file.

#### Work with database

* Click [Load Sites] to show the list of sample sites.
* Click on a sample site to load the site setting only
* Doubleclick on sample site to crawled links from database.
* Click on [x] to delete site from database
* Click [Save Site] will save site setting with crawled links to database (sample.mdb)

If everything is tested fine, may click [Save All to File] to crawl all pages to html files.


## Source Code

It is single html/js program ([pp-web-crawler.html](source/pp-web-crawler.html)) about 300 lines. 

## Modification History

* 2021/06/28, v0.30, first version.
* 2021/07/02, v0.35, add sample sites.
* 2021/07/09, v0.40, save links to db, and misc enhancement
* 2021/07/11, v0.50, work with database, work with local files, and misc enhancement

## License

MIT
