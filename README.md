# 2022 REEES Think Tank Digital Humanities Resources

This document is a series of resources for the 2022 [Howard University REEES Think Tank](https://www.reeesthinktank.com/) to advance diversity and inclusion in Russian, East European, and Eurasian Studies (REEES). This document provides some brief background on Digital Humanities (DH) methods and links to some major tools and tutorials for them. It also includes a list of open access online resources for REEES. This is not meant to be a comprehensive guide to either, but merely a starting point. It also includes some examples of projects using these methods to serve as inspiration for what types of results can be achieved.

## DH Overview

What is Digital Humanities (DH)? In brief, DH is a variety of digital tools and methods meant to complement and enhance traditional methods of humanities research. There and many different tools and methods that count as DH. The [Carnegie Mellon Digital Humanities Literacy Guidebook](https://cmu-lib.github.io/dhlg/) is a great starting point to learn more about DH broadly as well as many different tools and methods. The site also includes videos with scholars showing how they used particular methods to execute their research projects.

## Major Different DH Methods for REEES Research

There are many different DH methods but these following NUMBER are the most likely to be used by REEES projects.

### GIS Mapping

Geographic information system (GIS) is the act of making maps in computer software. There are many different GIS softwares. The company ESRI makes both webmapping and desktop software. [ArcGIS Online](https://www.arcgis.com/index.html) is a great starting point for building maps in a web interface. ESRI also publishes [excellent tutorials](https://learn.arcgis.com/en/projects/get-started-with-arcgis-online/) for how to get started with their software. After making a map in ArcGIS online, users can then transfer their maps to the [ArcGIS StoryMaps](https://storymaps.arcgis.com/) platform to build interactive multimedia web projects. The StoryMaps platform serves as a way to bring together text, maps, and images and publish them as an interactive site for free. ESRI also has [tutorials](https://storymaps.arcgis.com/stories/cea22a609a1d4cccb8d54c650b595bc4) for how to use this interface.

While ESRI's free web software is decent, the free accounts severely limit the types of actions that can be taken in this platform. ESRI offers a very powerful desktop software called [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview), which requires an expensive license to use. Some students may be able to get a free license from their university. ESRI makes [tutorials](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview) for their desktop software as well.

There is also a free, open source alternative to ArcGIS Pro that works almost as well, if not better for certain operations, called [QGIS](https://www.qgis.org/en/site/). Those interested in using QGIS should get started with [this tutorial by Lincoln Mullen](https://lincolnmullen.com/projects/spatial-workshop/qgis.html), which explains some of its utility for historical analysis.

Users can generate their own data for use with GIS software. In other cases, they can download some ready developed files for use in the software. Some helpful free data sources for REEES are: 

[Historical shapefiles](https://icr.ethz.ch/data/cshapes/)

[Heidelberg University shapefile for 1926 USSR census](https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/data/10064)

[Electronic Repository of Russian Historical Statistics](https://datasets.iisg.amsterdam/dataverse/RISTAT)

[GeoPortOst: Thematic and Hidden Maps of Eastern and Southeastern Europe](http://geoportost.ios-regensburg.de/en/)

[Memorial](https://www.memo.ru/ru-ru/collections/)

[Germans from Russia Settlement Locations](https://www.germansfromrussiasettlementlocations.org/p/maps.html) 

Historic maps are also excellent sources for projects in REEES. Some great collections of maps are below:

[Та сторона](http://tastorona.su/)

[Mapster](http://igrek.amzp.pl/)

[Indiana University Bloomington Maps: Russian Military Topographic Map Collection](https://webapp1.dlib.indiana.edu/images/splash.htm?scope=images/VAC9619)

[Runivers](https://runivers.ru/mp/)

[David Rumsey Historical Map Collection](https://www.davidrumsey.com/)

The following list includes books, articles, and existing projects of interest dealing with spatial methods either broadly or specifically for REEES:

[A Baltic Pilgrimage in 1912 Story Map](https://www.balticorthodoxy.com/pilgrimage)

[Copernico: History and Cultural Heritage in Eastern Europe](https://www.copernico.eu/en/start)

[George Kennan’s Kamchatka Expedition Story Map](https://storymaps.arcgis.com/stories/3c68c41d6c4840e9a0a3f71b40cde221)

[The Holocaust by Bullets map](http://www.yahadinunum.orgwww.yahadmap.org/#map/)

[Imperiia Project](https://imperiia.scalar.fas.harvard.edu/imperiia/index)

[Imperiia Project: Urban Legends](https://imperiia.omeka.fas.harvard.edu/exhibits/show/urban-legends)

[Knowles, Anne Kelly. 2014. Geographies of the Holocaust](https://www.google.com/books/edition/Geographies_of_the_Holocaust/wqFrAwAAQBAJ?hl=en&gbpv=0)

[Measuring Ghettos](https://ghettos.digital/)

[Soviet Air Network 1948 animated map by Seth Bernstein](https://vimeo.com/146043317)

[Tour of the Pühtitsa Icon of the Assumption of the Virgin Mary in 1907 Story Map](https://www.balticorthodoxy.com/icon)

Note: much of the information presented in this GIS section was already compiled by the author of this file for the *Peripheral Histories?* blog and its [Digital Spatial Resources Page](https://www.peripheralhistories.co.uk/digital-spatial).

### Text Analysis

Text analysis, sometimes also referred to as text mining, is the process of automatically extracting information from a body of text. Text analysis is generally concerned with the content of a large body of texts, known as the corpus. There are many different tools for text analysis, some are web interfaces, some are desktop programs, and others are code scripts that use programming languages such as R or Python. A person may use these different tools for different studies of a body of texts such as for frequency analysis, sentiment analysis, or pattern recognition. [*Digital Dostoevsky*](https://digitaldostoevsky.com/) is an example of a text analysis project for the REEES field. 

A great simple way to get started with text analysis is the free website [Voyant](https://voyant-tools.org/). Voyant has its own comprehensive [tutorial](https://voyant-tools.org/docs/#!/guide/start) to get you up and running analyzing texts with different study methods. Voyant also works in multiple languages, which is very helpful for REEES.

A more powerful desktop based software for more complicated corpus analysis is [ActConc](https://www.laurenceanthony.net/software/antconc/). The software publisher created a [simple guide](https://www.laurenceanthony.net/software/antconc/resources/help_AntConc321_english.pdf) for getting started.

Users with experience with Python might prefer to do text analysis with the [Natural Language Toolkit, NLTK](https://realpython.com/nltk-nlp-python/) package.

One of the best parts about text analysis is that it can be very easy to build datasets for studies. Newspaper articles and diaries are examples of excellent sources. The *Peripheral Histories?* blog has an [excellent list of online primary sources](https://www.peripheralhistories.co.uk/online-primary-sources) for REEES that are open access, many of which are perfect for text analysis. 

### Timelines

Timelines can both be used as a research and publishing tool. They are especially useful for historical projects that rely heavily on explaining and emphasizing the chronology of events. The best simple tool for making a strong and shareable timeline is [TimelineJS](https://timeline.knightlab.com/). Getting started is as easy as following the steps on [this page](https://timeline.knightlab.com/#make).

Timelines can also be effectively joined with other forms of digital analysis. One great example of a cross between a timeline and text analysis is the [*Beyond the Ant Brotherhood*](https://www.colloquy.us:8443/Tolstoy/#home) project, which seeks to understand what events, people, and writings influenced Leo Tolstoy. 

### Network Analysis

Network analysis is a set of techniques that uses networks and graph theory to study relationships between actors and the social structures that arise from these relationships. Network analysis can be very difficult to master but also very rewarding. One of the most commonly used programs for network analysis is [Gephi](https://gephi.org/). Gephi offers both [written and video tutorials](https://gephi.org/users/).

## DH Tools for Publishing

As the GIS section above noted, you can use the [ArcGIS StoryMaps](https://storymaps.arcgis.com/) platform to build interactive multimedia web projects. You can also use [TimelineJS](https://timeline.knightlab.com/) to build and share interactive timelines.

If you are more interested in building your own website, [Wordpress](https://wordpress.com/) is a simple and free platform to do so. Alternatively, you can build simple sites for free via [GitHub](https://github.com/), which is where this document was written and hosted. GitHub repositories can be edited collaboratively. This particular page was written with a type of text encoding or formatting known as markdown. Markdown is very easy to pickup markup language for formatting text. [This cheat sheet](https://www.markdownguide.org/cheat-sheet/) is enough to make a similar webpage.

GitHub and Wordpress are excellent ways to build sites that host other forms of creative projects as well. For example, you may wish to record a podcast episode or series on a given topic. You can host your files with both of these sites. You can also embed timelines and maps with these sites. Another form of creative content production is to make a movie with free software like iMovie. You can then upload your video to YouTube and embed the video in your page with additional information that introduces it.

Another option for collaborative and interactive projects is [Canva](https://www.canva.com/), which has a free option. Canva will also let you make videos and combine text with other multimedia in a shareable format. You can find more out about how to use Canva with their [tutorial site](https://www.canva.com/designschool/tutorials/).

## How to find DH Help

Often, your two best bets for getting help with Digital Humanities tools, methods, and publication are Google and your institution's library. Simple Google searches such as "GIS tutorial" will yield helpful results. There are often plenty of trouble shooting websites for whatever error message you might get with software as well.

These days, many libraries have digital scholarship departments or librarians. The best way to get started is to search "digital humanities" or "digital scholarship" plus your university's name. Howard University has [*Digital Howard*](https://dh.howard.edu/about.html) for example. The contact listed there will be a very helpful resource in terms of finding experts who can help you with particular tools or methods if they do not know a particular tool or method themselves. Libraries also often host training workshops in DH research and publishing methods. 
