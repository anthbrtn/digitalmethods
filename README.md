
# Table of Contents

1.  [Introduction](#orgdc0fd9d)
    1.  [About navigating](#org98145d1)
2.  [Data collection](#org43f396c)
    1.  [Scraping](#orgc6b792c)
    2.  [Capturing and exploring data](#org30516ef)
3.  [Data organization and maintenance](#orgd943233)
    1.  [Data reading](#orgbd53587)
    2.  [Data maintenance](#orgd72812f)
4.  [Data analysis and visualization](#org24df978)
    1.  [Visualization](#orgfe94d2b)
    2.  [Analysis](#org434b523)
5.  [Sources / see more](#org97bf486)
    1.  [University of North Carolina Digital Humanities Tools list](#org2bc1b4b)
    2.  [Duke University Digital Humanities Tools list](#orgc070df7)
    3.  [DHtech’s Awesome Digital Humanities tools list](#org5208eba)
    4.  [University of Amsterdam Digital Methods Initiative’s tool database](#org6b43868)
    5.  [Sciences Po médialab tools](#orgcceca96)
    6.  [dbohan’s Awesome Structured Text Tools list](#org8be4cc2)



<a id="orgdc0fd9d"></a>

# Introduction

A list of digital tools, cribbed from a bunch of resources ([5](#org97bf486)) and put together. Created in collaboration with Dr. Greg Elmer.


<a id="org98145d1"></a>

## About navigating

This document is organized according to the sort of flow that a digital methods research project would undertake. If you’re crunched for time, your best bet is probably to search for a keyword that you’re looking for (if you’re reading this in a browser, something like `Ctrl+F` or `CMD+F` should pull up a search box; if you’re reading this outside of a browser somehow, you probably know how to grep for text).


<a id="org43f396c"></a>

# Data collection


<a id="orgc6b792c"></a>

## Scraping

### Loot.photo

<https://loot.photo/>
This website allows you to dowload photos and videos from a given tweet instantly.

### Amazon Related Product Graph

<https://github.com/digitalmethodsinitiative/arpg>

This PHP script allows you to enter a (set of) ASIN(s) and crawl its
recommendations up til a user-specified depth.


### Amazon Book Explorer

<http://tools.digitalmethods.net/beta/amazon>

Provides different analytics for Amazon.com&rsquo;s book search


### App Tracker explorer

<https://tools.digitalmethods.net/beta/appTrackers>

The DMI’s App Tracker Tracker is a tool to detect a set of predefined fingerprints of known tracking technologies or other software libaries.


### `.csv` Get

<https://github.com/fizx/csvget/tree/master>

Scrape elements from a website and generate a .csv file.

Use: grab select data like headlines, categories, etc.


### Discus Comment Scraper

<http://tools.digitalmethods.net/beta/disqusScraper>

This tool scrapes threads and comments from websites implementing the <http://www.disqus.com/Disqus> commenting system.


### Github organizations meta-data lookup

<http://tools.digitalmethods.net/beta/githubOrgsLaunch>

Extract the meta-data of organizations on Github


### Github repositories meta-data lookup

<http://tools.digitalmethods.net/beta/githubReposMeta/>

Extract the meta-data of Github repositories


### Github repositories scraper

<https://tools.digitalmethods.net/beta/githubRepos/>

Scrape Github for forks of projects


### Github scraper

<https://tools.digitalmethods.net/beta/github/>

Scrape Github for user interactions and user to repository relations


### Github user meta-data lookup

<https://tools.digitalmethods.net/beta/githubUserMeta/>

Extract meta-data about users on Github


### GithubContributorsScraper

<https://tools.digitalmethods.net/beta/githubContributors/>

Find out which users contributed source code to Github repositories


### Google Autocomplete

<http://tools.digitalmethods.net/beta/scrapeGoogle/autocomplete.php>

Retrieves autocomplete suggestions from Google


### Google Image Scraper

<http://tools.digitalmethods.net/beta/googleImages>

Query images.google.com with one or more keywords, and/or use images.google.com to query specific sites for images.


### Google Play Similar Apps

<http://tools.digitalmethods.net/beta/googlePlaySimilar>

DMI Google Play Similar Apps is a simple tool to extract the details of individual apps, collect ‘Similar&rsquo; apps, and extract their details.


### Google Reverse Image scraper

<http://tools.digitalmethods.net/beta/googleReverseImages>

Scrape Google for occurance of images


### Googlescraper (Lippmannian Device)

<http://tools.digitalmethods.net/beta/searchEngineScraper/>

Batch queries Google. Query the resonance of a particular term, or a series of terms, in a set of Websites.


### Image Scraper

<http://tools.digitalmethods.net/beta/imagesDeep>

Scrape images from a single page.


### Instagram Loader

<https://tools.digitalmethods.net/beta/instagramLoader/>

Easily scrape images from Instagram based on hashtag, location, or user data. If the website asks you for a login, try from a different internet connection.


### Internet Archive Wayback Machine Link Ripper

<https://tools.digitalmethods.net/beta/internetArchiveWaybackMachineLinkRipper>

Scrapes links from the Wayback Machine


### Internet Archive Wayback Machine Network Per Year

<https://tools.digitalmethods.net/beta/waybackNetworkPerYear/>

Enter a set of URLs and the archived versions closest to 1 July for a specific year are retrieved. Thereafter links are extracted and a network file is output.


### iTunes Store

<http://tools.digitalmethods.net/beta/itunesStore>

Query the iTunes store and grab both tabular and `.gdf` data regarding results.


### News Agencies Scraper

<https://tools.digitalmethods.net/beta/newsAgencies/>

Basic scraper for various news agencies for particular keywords and extract titles, images, dates and full text.


### Octoparse

<https://www.octoparse.com/>

An all-in-one solution for scraping websites, including the ability to scrape platform pages. Closed source, paid, and requires a sign-up, although the website offers a 14-day demo trial.

1.  Using Octoparse for Instagram

    Octoparse provides a tutorial for scraping Instagram. It can be found [on their website.](https://helpcenter.octoparse.com/hc/en-us/articles/360018842071-Scrape-data-on-Instagram)


### Search Engine Scraper

<https://tools.digitalmethods.net/beta/searchEngineScraper/>


### webscraper.io

<https://www.webscraper.io/>

A browser extension that allows you to build scrapers, scrape websites, and export data in .csv format. Closed-source, but the browser extension is free.


### Wikipedia TOC Scraper

<http://tools.digitalmethods.net/beta/wikitoc/>

Scrape Table of Contents for revisions of a wikipedia page and explore the results by moving a slider to browse across chronologically ordered TOCs.


### Wikipedia categories scraper

<https://tools.digitalmethods.net/beta/wikipediaCategoryAnalysis>

Scrape Wikipedia for the categories of articles and the categories of related articles in different languages.


### Wikipedia Edits Scraper and IP Localizer

<http://tools.digitalmethods.net/beta/wikipedia2geo/>

Scrapes Wikipedia history and does IP to Geo for anonymous edits


### YouTube Comment Scraper

<https://github.com/philbot9/youtube-comment-scraper-cli>

Scrape comments from YouTube pages.

Use: uh… scrape comments from YouTube pages.


<a id="org30516ef"></a>

## Capturing and exploring data


### 4CAT: Capture and Analysis Toolkit

<http://4cat.oilab.nl/>

Create datasets from webforums such as 4chan and Reddit and perform textual analysis on the resulting datasets. Login required.


### Censorship Explorer

<http://tools.digitalmethods.net/beta/proxies>

Check whether a URL is censored in a particular country by using proxies located around the world.


### Expand Tiny Urls

<http://tools.digitalmethods.net/beta/expandTinyUrls/>

Expands URLs that have been shortened by tools like tinyurl.com or bit.ly.


### Geo IP

<http://tools.digitalmethods.net/beta/geoIP/>

Translates URLs or IP addresses into geographical locations


### Infoscapelab DMi-TCAT

<https://tcat.infoscapelab.ca>

**Login required; contact me at ab {at} anthbrtn.com**

An instance of the University of Amsterdam’s Twitter Capture and Analysis toolkit accessible to Ryerson students.


### Link Ripper

<http://tools.digitalmethods.net/beta/linkRipper/>

Capture all internal links and/or outlinks from a page.


### Robots.txt Discovery

<http://tools.digitalmethods.net/robots>

Display a site&rsquo;s robot exclusion policy.


### Screenshot generator

<http://tools.digitalmethods.net/beta/screenshotGenerator>

Produce screenshots for a list of URLs


### Source Code Search

<http://tools.digitalmethods.net/beta/sourceCodeSearch>

loads a URL and searches for patterns in the page&rsquo;s source code


### Text Ripper

<http://tools.digitalmethods.net/beta/textRipper>

Rip all non-html (i.e. text) from a specified page.


### Timestamp Ripper

<http://tools.digitalmethods.net/beta/timestamp>

Rips and displays a web page&rsquo;s last modification date (using the page&rsquo;s HTML header). Beware of dynamically generated pages, where the date stamps will be the time of retrieval.


### Triangulation

<http://tools.digitalmethods.net/beta/triangulate/>

Enter two or more lists of URLs or other items to discover commonalities among them. Possible visualizations include a Venn Diagram.


### Netvizz Tumblr toolkit

<https://tools.digitalmethods.net/netvizz/tumblr/Launch>

Analyze co-hashtags and other basic text information from Tumblr posts.


### twXplorer

<https://twxplorer.knightlab.com/>

Search recent tweets and analyze them.

Use: if you want a quick analysis that the TCAT doesn’t provide.


### Wikipedia Cross-Lingual Image Analysis

<http://tools.digitalmethods.net/beta/wikipediaCrosslingualImageAnalysis>

Makes the images of all language versions of a Wikipedia article comparable.


### Wikipedia Entry Check

<http://tools.digitalmethods.net/beta/wikipediaEntryCheck/>

This tool checks if the issues exist as a Wikipedia page, i.e., an article. If it exists it checks whether the organization is mentioned on that page.


### YouTube Data Tools

<https://tools.digitalmethods.net/netvizz/youtube/>

A collection of simple tools for extracting data from the YouTube platform via the YouTube API v3.


<a id="orgd943233"></a>

# Data organization and maintenance


<a id="orgbd53587"></a>

## Data reading


### Agnes

<http://www.secretgeek.net/agnes/twoWay.html>

Convert `.csv` data to `.json` and vice-versa.

Use: much API data is returned as `.json`-formatted files.


### `.csv` to Table

<https://github.com/vividvilla/csvtotable>

Convert `.csv` files to searchable and sortable HTML table.

Use: visualize and analyze data formatted in `.csv`


### eBay’s tabular data file utilities

<https://github.com/eBay/tsv-utils>

Analyze data saved with `tab` delimiters, as opposed to the standard `comma`. Yes, it’s *that* eBay.

Use: perform maintenance and reading on `tab`-separated files.


### Mario

<https://github.com/python-mario/mario>

Gain access to the Python programming language’s variety of tools and libraries to perform analysis on `.csv`, `.json`, `.html` files and more.

Use: pretty much any analysis and conversion under the sun; it’s a powerful toolkit but requires reading the documentation to figure out your own use-case.


### networkX

<http://networkx.github.io/>

A Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.

Use: analyze graphs and networks and return them using python.


### Nodegoat

<https://nodegoat.net/>

A web-based data management, network analysis & visualisation environment.

Use: an all-in-one suite for analyzing, managing and graphing data.


### PapaParse

<https://www.papaparse.com/demo>

A browser-based tool that allows you to parse and analyze `.csv` data.

Use: look for basic patterns and characteristics of a `.csv`.


### XSV

<https://github.com/BurntSushi/xsv>

A command-line toolkit to analyze and investigate .csv files.

Use: easily find out things like frequencies of data, different values, and correlations.


### Tad

<https://github.com/antonycourtney/tad>

Tad is a desktop application for viewing and analyzing tabular data such as `.csv` files.

Use: easily create “pivot tables” to analyze your data, among other csv functions.


### Tapor-coding-tools

<https://github.com/TAPoR-3-Tools/Tapor-Coding-Tools>

A collection of coding tools, mostly in python, to analyze text.

Use: worth exploring to find programming examples for the analysis of text. Many use-cases in the repository.


<a id="orgd72812f"></a>

## Data maintenance


### Ron’s `.csv` Editor

<https://www.ronsplace.eu/products/ronseditor>

Deal with massive .csv files easily.

Use: organize, read, and analyze .csv files that would normally crash a spreadsheet program.


### scrubcsv

<https://github.com/faradayio/scrubcsv>

Remove bad lines from a .csv file and normalize the rest.

Use: sometimes .csv files exported from SQL databases have errors; many tools here, such as the YouTube data tools and the Twitter Capture and Analysis toolkit are exported as such. This tool discards those error-ridden rows and allows you to read the files.


### OpenRefine

<https://openrefine.org/>

A tool for cleaning data; transforming it from one format into another; and extending it with web services and external data.  OpenRefine can be used to scrape data from websites or convert data between formats.  It also makes it easy to save the processing steps to a file that can be loaded back into the tool at a later time, making it easy to repeat the process again on a different set of data.


<a id="org24df978"></a>

# Data analysis and visualization


<a id="orgfe94d2b"></a>

## Visualization


### Bubble Lines

<http://tools.digitalmethods.net/beta/bubbleline/>

Input tags and values to produce relatively sized bubbles. Output is an svg.


### Concordle

<https://folk.uib.no/nfylk/concordle/>

Generate word clouds and see word correlations in a given text. Calls itself the “not-so-pretty cousin of Wordle” (below).

Use: basic text analysis of word frequencies, along with visualization.


### Colors For Data Scientists

<http://tools.medialab.sciences-po.fr/iwanthue/>

Generate and refine palettes of optimally distinct colors. (by Sciences-Po)


### Datawrapper

<https://datawrapper.de>

Datawrapper allows users to create a variety of basic charts and graphs using submitted tabular data.


### Deduplicate

<http://tools.digitalmethods.net/beta/deduplicate>

Replicates the tags in a tag cloud by their value


### Dorling Map Generator

<http://tools.digitalmethods.net/beta/dorling/>

Input tags and values to produce a Dorling Map (i.e. bubbles). Output is an svg.


### Chronos Timeline

<http://hyperstudio.mit.edu/software/chronos-timeline/>
Chronos allows scholars and students to dynamically present historical data in a flexible online environment.


### Lippmannian Device To Gephi

<http://tools.digitalmethods.net/beta/lippmannianDeviceToGephi>

This tool allows one to visualize the output of the Lippmannian device as a network with Gephi.


### Raw Text to Tag Cloud Engine

<http://tools.digitalmethods.net/beta/tagcloud/>

Takes raw text, counts the words and returns an ordered, unordered or alphabetically ordered tagcloud.


### rawgraphs.io

<https://rawgraphs.io>

Rawgraphs is an online tabular data processing program that allows users to create advanced charts and graphs using submitted tabular data.


### Scene

<https://scene.knightlab.com/>
Create a multimedia story told through 3D “VR” tools.


### Seealsology

<https://densitydesign.github.io/strumentalia-seealsology/>

Create a graph out of the &ldquo;see also&rdquo; networks between given Wikipedia pages.


### Simile

<http://simile-widgets.org/>

A collection of free, open-source web widgets, mostly for data visualizations.


### Soundcite

<http://soundcite.knightlab.com/>

Stitch together audio from various sources and embed it within a readable text.


### Storyline

<http://storyline.knightlab.com/>

Easy-to-use tool to build an annotated, interactive line chart.


### StoryMap

<http://storymap.knightlab.com/>

Create a narrative, sequential story that moves through locations on a map.


### Table to Net

<http://tools.medialab.sciences-po.fr/table2net/>

Extract a network from a table. Set a column for nodes and a column for edges. It deals with multiple items per cell. (by Médialab Sciences-Po)


### Tag Cloud Combinator

<http://tools.digitalmethods.net/beta/tagCloudCombinator>

Enter two or more tag clouds and the values of each tag will be summed.


### Tag Cloud Generator

<http://tools.digitalmethods.net/beta/svgcloud/>

Input tags and values to produce a tag cloud. Output is in SVG.


### Tag Cloud HTML Generator

<http://labs.polsys.net/tools/visual/tagcloud/>

Input tags and values in wordle format to produce a HTML tag cloud or tag list.


### Tag Cloud To Wordle

<http://tools.digitalmethods.net/beta/tagcloudToWordle/>

This tool allows one to transform a normal tag cloud into a fancy Wordle one.


### TimeGlider

<http://timeglider.com/>

A web-based timeline builder


### Timeline

<http://timeline.knightlab.com/>

Create a visually-appealing annotated timeline.


### TimeToast

<http://www.timetoast.com/>

A tool for creating timelines which can be added to a website or blog.


### uMap

<https://umap.openstreetmap.fr/en/>

Create resuable, static, embeddable maps from OpenStreetMap data.


### Viewshare

<http://viewshare.org/>

A platform that helps you create customized “views” such as interactive maps and timelines.


### VisiData

<https://www.visidata.org/>

An interactive, command-line tool for analyzing and visualizing tabular data.

Use: get quick visualizations and perform other data-scientific methods on tabular data.


### Wordle

<http://www.wordle.net/>

Generate word clouds (clouds of words that size the words based on frequency) for a given text.

Use: visualize frequency of words in a given corpus.


<a id="org434b523"></a>

## Analysis


### Compare Lists

<http://tools.digitalmethods.net/beta/analyse>

Compare two lists of URLs for their commonalities and differences.


### ComplexSentimentAnalysis.ipynb

<https://github.com/sgsinclair/alta/blob/dc47e4b47b133cee24a85e9817592971e67681cd/ipynb/utilities/ComplexSentimentAnalysis.ipynb>

A [iPython notebook](https://jupyter.org/) that walks the user through performing complex sentiment analysis of passages like Tweets for sentiment analysis. You can download the iPython notebook and run it yourself (which requires Jupyter lab, linked in the previous sentence), or read the text for an example.

Use: learn how to use python for sentiment analysis; perform sentiment analysis on texts.


### Gephi

<https://gephi.org/>

Gephi is a visualization and exploration software for all kinds of graphs and networks.

Use: analyze the `.gdf` and `.gxml` files returned by many scraping and collection tools. The most robust tool available, but sometimes slow and hard to configure; an online alternative is **Polinode**, below.


### Harvester

<http://tools.digitalmethods.net/beta/harvestUrls/>

Extract URLs from text, source code or search engine results. Produces a clean list of URLs.


### Juxtapose

<http://juxtapose.knightlab.com/>

Easily compare two images within a frame.


### Language Detection

<http://tools.digitalmethods.net/beta/text_cat/>

Detects language for given URLs. The first 1000 characters on the Web page(s) are extracted, and the language of each page is detected.


### Lippmannian Device

<https://tools.digitalmethods.net/beta/lippmannianDevice/>

The Lippmannian device is named Walter Lippmann, and provides a coarse means of showing actor partisanship.


### NodeXL

<http://nodexl.codeplex.com/>

NodeXL is a plugin to Microsoft Excel that allows you to visualize and analyze data beyond what the program has normally built in.

Use: visualize and analyze data using Microsoft Excel (although for a faster, lighter, and free alternative, see [LibreOffice](https://www.libreoffice.org/)).


### Palladio

<http://hdlab.stanford.edu/palladio/>

Various analyses of historical data in tabular format.


### Polinode

<https://www.polinode.com/>

**Login required**

Polinode is an online tool that allows for the opening and basic manipulation of `.gdf` files.

Use: analyze the `.gdf` and `.gxml` files returned by many scraping and collection tools. An online tool that is not as powerful as **Gephi**, above, but easier to understand and get started with.


### Rip Sentences

<http://tools.digitalmethods.net/beta/sentences>

Rip text from a specified page and force line breaks between sentences.


### Umigo


### Table 2 Net

<https://medialab.github.io/table2net/>

Parse tabular data for relationships and convert into a table.


### TLD counts

<http://tools.digitalmethods.net/beta/tldCounts/>

Enter URLS, and count the top level domains.


### Voyant

<https://voyant-tools.org/>

A web-based tool that provides text reading and basic analysis based on copy-pasted text.


<a id="org97bf486"></a>

# Sources / see more


<a id="org2bc1b4b"></a>

## University of North Carolina Digital Humanities Tools list

<http://digitalhumanities.unc.edu/resources/tools/>


<a id="orgc070df7"></a>

## Duke University Digital Humanities Tools list

<https://digitalhumanities.duke.edu/tools>


<a id="org5208eba"></a>

## DHtech’s Awesome Digital Humanities tools list

<https://github.com/dh-tech/awesome-dhtools>


<a id="org6b43868"></a>

## University of Amsterdam Digital Methods Initiative’s tool database

<https://wiki.digitalmethods.net/Dmi/ToolDatabase>


<a id="orgcceca96"></a>

## Sciences Po médialab tools

<http://tools.medialab.sciences-po.fr/>


<a id="org8be4cc2"></a>

## dbohan’s Awesome Structured Text Tools list

<https://github.com/dbohdan/structured-text-tools>

