# Trucking Project

# Project Overview

Truckin' is a site that aims to directly aid the trucking and shipping industry.

So much of the average person's everyday life relies on e-commerce and other things

Reliability is key in industries like e-commerce especially with their high use - Truckin will increase reliability by....

| # | Ways Truckin' Helps! |
|-----:|-----------|
|     1|Providing truckers with access to relevant climate data|
|     2|Enabling truckers to coordinate stops along their route at optimal times|
|     3|Helping truckers visualize their routes in an easy-to-digest format |

# Page Descriptions

## htmlpage.html - the main page

![image](https://github.com/jmklr/TruckingSite/assets/142524952/6e38ca4d-d3f2-4452-8783-b78b830f14f2)


This page serves as a "home" page for the site! It shares a navbar at the top with all other pages to provide optimal usability. The page features a prominent button to direct users towards the route planning application. It gives brief breakdowns of relevant applications of the site and why it should be used.

## secondpage.html - the route planning application

![image](https://github.com/jmklr/TruckingSite/assets/142524952/3fbb82f4-dbbd-44f2-8db1-d53a39220003)


secondpage.html will be used for the route planning application. The name is entirely tentative. The page is very bare bones at the moment, with it's only true functionality being using JavaScript to find the latitude and longitude of the user and outputting it into a table. 

## signup.html - user signup page

![image](https://github.com/jmklr/TruckingSite/assets/142524952/57487fe8-0430-4038-868a-dd4aa77df165)


signup.html is a simple page that will stay simple when entirely fleshed out. Right now it just gives a prompt for a user to give their e-mail for update e-mails. 

# Research Summary

Research for this project led me to a few sites and repositories:

## https://roadtrippers.com/

Roadtrippers has a feature that shows major tourism destinations along the planned route. Truckin' aims to include a similar feature that shows truck stops, hotels, rest areas, etc. Roadtrippers also showcases pre-chosen estinations on their main page, which could be flipped into a feature for Truckin' like showing popular destinations or climate data at recent destinations chosen. The website was a bit difficult to research as some features were locked behind a paywall. It would not be a smart business move for Truckin' to do something similar, as I believe it would discourage potential users.

## https://mapquest.com/

One thing I noticed instantly with mapquest was that the URL changed when selections were made. An example would be when I demoed the site I picked a route from Pittsburgh to Atlanta, which gave the url .../from/us/pa/pittsburgh.../to/us/ga/atlanta-...../. Mapquest offers different options for routes like least amount of distance, which is something Truckin' should look to incorporate. Some effective uses of this could be shortest distance, least amount of time, or no tolls. Mapquest doesn't mention tolls - which is something Truckin' will definitely need.

## https://www.trippy.com/

Trippy had a feature that immediately jumped out to me as very useful for my target audience - it suggests potential overnight stays. It even suggests them in places truckers frequent like Fort Chiswell, VA. It also highlights cities the routes pass through, which is something Truckin' needs to do in order to effectively communicate relevant climate data. 

## https://github.com/batuhankok/html-distance-route-maps/

This repo is built on Google Maps API which could be a useful API to use in the future for implementing map functionalities. However, the formatting of the site is insanely dated, so the only inspiration Truckin' will likely take from this repo is their use of the API. 

## https://github.com/roxyvaught/Vacation-Planner/blob/master/README.md

This repo has a lot of features that have direct applications to Truckin' even if it has a widlly different purpose. This repo is a similar site built to plan trips to the National Parks. A lot of these features could be flipped into planning trips to/from major shipping warehouses and can show climate data. 
