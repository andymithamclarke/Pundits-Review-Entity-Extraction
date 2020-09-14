<img src="https://i.ibb.co/ZXVNVY5/pr-logo-plain-opauq.png" width="7.5%" height="7.5%">

# Pundits Review Entity Extraction
Development of the process used in the Pundits Review website to recognise Premier League player & club entities in news articles - https://www.punditsreview.com/


> Pundits Review scrapes and processes news articles about the Premier League in order to give players and teams a review score each week. Each Monday, the project collects articles, divides them into phrases, identifies the player or club being referred to and then predicts the sentiment of the phrase. See more on how it works <a href="https://www.punditsreview.com/howitworks">here</a>!


## About this repository
This repository shows the progression of the methods used to recognise the players being written about in a phrase within a football news article. The methods employ a spacy model to recognise the syntatic dependencies of words in a phrase. My final solution matches words which; a) Appear as a proper noun | b) Are longer than 3 characters | c) Appear in key syntactic dependency positions | d) Are listed as a player or club identifier. 

## Contents

#### <a href="https://github.com/andyclarkemedia/Pundits-Review-Entity-Extraction/blob/master/1st_Attempt.ipynb">Attempt 1</a>
Attempt 1 explores different ways to recognise a player entity using a spacy model

#### <a href="https://github.com/andyclarkemedia/Pundits-Review-Entity-Extraction/blob/master/Evaluating_Approaches.ipynb">Evaluating Approaches</a>
This notebook compares 10 different approaches to recognising player / club entities. Independent variable: key syntactic dependency position

#### <a href="https://github.com/andyclarkemedia/Pundits-Review-Entity-Extraction/blob/master/annotated_data.csv">Annotated Data</a>
Manually annotated (sentiment & player target) set of 500 rows of sample data taken from <a href="https://www.mirror.co.uk/sport/football/match-reports/">The Mirror - Match Reports</a>

## Associated Repositories

##### <a href="https://github.com/andyclarkemedia/Pundits-Review">Pundits Review</a> - 11/09/2020 - Complete directory for Pundits Review web application.
##### <a href="https://github.com/andyclarkemedia/Pundits-Review-Resources">Resources</a> - Data, images & Python dictionary of Premier League players & teams
##### <a href="https://github.com/andyclarkemedia/Pundits-Review-Scraping">Scraping</a> - Development of the scraping process used to collect data
##### <a href="https://github.com/andyclarkemedia/Pundits-Review-Entity-Extraction">Entity Extraction</a> - Development of the process used to recognise Premier League player & club entities within a news article

##
#### Any Questions ... <a target="_blank" href="mailto:clarkeAJ3@cardiff.ac.uk">Send me an email!</a>
