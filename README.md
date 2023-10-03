# Karlincam Projects

## What is [Karlincam](https://www.karlincam.cz)?

A website with different nature related topics. Some articles also translated into Chech. The factual content is related to Central Europe, especially the Czech Republic and the German-speaking regions. Visit me and my best wife of all at [https://www.karlincam.cz](https://www.karlincam.cz).

However, some features are based on specially configured applications and developments of versatile software solutions. Partly with dedicated hardware, like the [Raspberry Pi](https://www.raspberrypi.com/) or the [AudioMoth](https://www.openacousticdevices.info/audiomoth).

## This Repository

This repository combines the individual different projects and configurations that are managed thematically as individual repositories. I give a brief overview of each here. Some projects are not yet fully implemented. In this case, the associated repository is not yet public. 

# Projects

## Web page [www.karlincam.cz](www.karlincam.cz)

It's a simple wordpress page set up with Docker. I think, there is no reason to decripe details here.

## [search.karlincam.cz](https://search.karlincam.cz)

Not just another search engine. It specializes in hand-selected websites on various topics related to nature in the Central European region. Especially of the German and Czech language area.

This project was created as a summer project 2023. The hollidays in the summer of 2023 were too hot to make any progress on the reconstruction of the very old house in Karlin. So we slept long and the evenings were also very long. Time enough to set up and configure an alternative search engine for special nature related content. While the technical details are in the foreground here, it has to be said that the manual research of the web sites to be crawled is very time-consuming in this particular case. In particular, specific configurations must be made for almost every source in order to index only the content that is actually relevant. And there are still individual cases where we could not find a solution.

This special search engine is based on the [YaCy project](https://yacy.net/) but is not coupled to the YaCy freeworld network. This search and indexing system is rich-full with configurations to crawl only relevant content. Despite we need some more tricks to collect the right web pages and contents. So I added [Privoxy](https://www.privoxy.org/) as "man in the middle" in order to filter out some non relevant content, like incorrectly configured robots.txt files. Additional I use Privoxy to manipulate web page content in order to filter out some non relevant content or links on this pages which makes crawling inefficient. In particular, I found a good trick to index selected Wikipedia content.

The project is not yet pushed to Github. But, comes in the next time.

## [birdnet at karlincam](http://birdnet.karlincam.de/)

Main part is a Raspberry Pi mini computer with the [birdnet-pi Project](https://github.com/mcguirepr89/BirdNET-Pi/). (At first see also at [www.raspberrypi.com](https://www.raspberrypi.com/news/classify-birds-acoustically-with-birdnet-pi).) But we would not be Karlincam if this would be installed as a single server application for only one use case. So we just send the live sound to a relay, which sends it on to our birdnet-pi. But not only there. Additional it send the content stream to my hosted root server with an icecast audio server. At the end this content is hosted by the [Locus Sonus Project](https://locusonus.org) and [Bird Weather](https://app.birdweather.com/stations/1036).

The project is not yet pushed to Github. But, comes in the next time.

Additional the sound is saved 24/7 into opus files. But the would be the next project:

## Mass analysis of audio files withe the birdnet neural network

This neural network is also used by the [birdnet-pi Project](https://github.com/mcguirepr89/BirdNET-Pi/). But in this case I search for a good solution to analyze mass data. The source can be sound data like saved in our [birdnet at karlincam](http://birdnet.karlincam.de/) project. But I orderd some [AudioMoth](https://www.openacousticdevices.info/audiomoth) devices. These devices doesn't have any recognition system. This would consume too much energy over the the use time: It is developed to digitize and save audio in the field over months. After this time you will have a full SD card. So wen need a good procedure to recognize the content. In my case: bird calls or bird songs.

Since neural networks work not absolutely correct, we use it in order to preprocess the data. Thats also the common use case of neural networks in science field research. But the procedure for these data is not yet written. I think, the repository will be open next year. Not before I have a running configuration.

Best regards,
Frank

herbrand@gmx.de
