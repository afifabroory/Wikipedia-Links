# !! DISCOUNTINUE !!
The project we are planning to scrape manully using script are not best solution and harmful for Wikipedia server. Instead, I am going to use database dump proivded by Wikimedia.

Some link that can be used for the main project of Wikipedia article network graph modeling:
- https://dumps.wikimedia.org/
- https://quarry.wmcloud.org/
- https://en.wikipedia.org/wiki/Wikipedia:Namespace
- https://www.mediawiki.org/w/index.php?title=Manual:Database_layout/diagram&action=render
- https://www.mediawiki.org/wiki/Manual:MediaWiki_architecture#Database_and_text_storage

# Wikipedia Links

This project is the base project for the "Wikipedia article network graph modeling" project.

In short, this project is for extracting links in the Wikipedia article and store links relationship into database. 

> *Important to know, the main design goal for this project is to model network graph relationships on specific topics only!*

The architecture of this project is too trivial to discuss or to show. But for the sake of documentation, here is the project architecture

![Project Architecture](Wikipedia-Links-Arch.png)

## Project Technologies
I am gonna use Python for the language and **???** for the database.

- Why Python? Because it's simple to use. So, I can focus on solving problems.
- Research is needed to decide which database I am gonna use.

## Some Notes
*About UI and application type.* The important part of the "Wikipedia article network graph modeling" project is a good User Interfaces. Because the data are extracted every time user input a *Wikipedia URL* manually. Having a good UI is better. For the sake of cross-platform I will choose a Web based application.

*About automation and data.* It's possible to extract automatically every time the program found URL from the lexical analysis. In that case, the relationship could be uncontrolled, because it will get anything the program found. This are also harmful for Wikipedia!
