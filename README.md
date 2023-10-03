# Karlincam Projects

## What is [Karlincam](https://www.karlincam.cz)?

A website with different nature related topics. Some articles also translated into Chech. The factual content is related to Central Europe, especially the Czech Republic and the German-speaking regions. Visit me and my best wife of all at [https://www.karlincam.cz](https://www.karlincam.cz).

However, some features are based on specially configured applications and developments of versatile software solutions. Partly with dedicated hardware, like the [Raspberry Pi](https://www.raspberrypi.com/) or the [AudioMoth](https://www.openacousticdevices.info/audiomoth).

## This Repository

This repository combines the individual different projects and configurations that are managed thematically as individual repositories. I give a brief overview of each here. Some projects are not yet fully implemented. In this case, the associated repository is not yet public. 

# Projects

## [search.karlincam.cz](https://search.karlincam.cz)

Not just another search engine. It specializes in hand-selected websites on various topics related to nature in the Central European region. Especially of the German and Czech language area.

This project was created as a summer project 2023. The hollidays in the summer of 2023 were too hot to make any progress on the reconstruction of the very old house. So we slept long and the evenings were also very long. Time enough to set up and configure an alternative search engine for special nature related content. While the technical details are in the foreground here, it has to be said that the manual research of the web sites to be crawled is very time-consuming in this particular case. In particular, specific configurations must be made for almost every source in order to index only the content that is actually relevant. And there are still individual cases where we could not find a solution.

This special search engine is based on the [YaCy project](https://yacy.net/) but is not coupled to the YaCy freeworld network. This search and indexing system is rich-full with configurations to crawl only relevant content. Despite we need some more tricks to collect the right web pages and contents. So I added [Privoxy](https://www.privoxy.org/) as "man in the middle" in order to filter out some non relevant content, like incorrectly configured robots.txt files. Additional I use Privoxy to manipulate web page content in order to filter out some non relevant content or links on this pages which makes crawling inefficient.

The project is not yet pushed to Github. But, comes in the next time.

## [birdnet at karlincam](http://birdnet.karlincam.de/)

