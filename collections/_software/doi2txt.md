---
layout: software
title: doi2txt
short-title: doi2txt
description: A tool to parse full text article sections based on a doi
tags: online-2020-software
function: data_collection
language: R
github: elizagrames/doi2txt
status: development
---
Screening articles for evidence synthesis is typically done using titles and abstracts, however, full text screening can be more efficient because there is no guessing involved when assessing if the methods of a study match inclusion criteria. Full text of articles is also necessary for coding article metadata, such as study location or types of data collected, or for analysing article content, such as with topic modelling. doi2txt facilitates full text article screening, coding, and analysis by retrieving plain text versions of journal articles based on a doi, if available,or bibliographic information such as title and authors when a doi is not available or known. It also contains functions for processing full text articles, such as coding articles from an ontology oftopics, or geocoding articles to get actual or approximate latitude and longitude.