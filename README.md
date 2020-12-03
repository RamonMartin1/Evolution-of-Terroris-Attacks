# Evolution of terrorist attacks worldwide
Focus of this project is storytelling and data vizualization so skip straight to powerpoint.
PP slides include external links to allow live interactive maps and graphs


## Table of Contents

* [Screenshots](#screenshots)
* [Features](#features) 
* [Technologies](#technologies)
* [Setup](#setup)
* [Metis](#metis)

## Screenshots

![Flask home page](public.flourish.studio/visualisation/3244335/)
![Flask recommender page](public.flourish.studio/visualisation/3383680/)

## Features

* Get anime recommendations for a MyAnimeList user ID **(only works on anime and user IDs scraped from MyAnimeList.net)** 

## Technologies

* Python 3.8
* HTML5
* CSS3
* Flask 1.1.2
* BeautifulSoup 4.9.1
* Selenium 3.141.0
* Docker 19.03.12
* Google Cloud Compute Engine
* MongoDB 4.4.0
* Scikit-learn 0.23.1
* Pandas 1.0.5
* Numpy 1.18.5
* Seaborn 0.10.1

## Setup

1. Clone this repo.
2. Run anime_recommender.py (may take a while due to web scraping, hence better to use a Docker container to deploy web scraper across multiple cloud instances).
    * If you want to scrape using the cloud, use Dockerfile in containers/container_1 directory.
3. Run app.py in flask directory to view Flask app.  

## Metis 

[Metis](https://www.thisismetis.com/data-science-bootcamps) is a 12-week accredited data science bootcamp where students build a 5-project portfolio. 
