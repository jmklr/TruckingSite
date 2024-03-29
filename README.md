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

## [Main Page](/TruckingProject/Pages/Index.cshtml)

![image](https://github.com/jmklr/TruckingSite/assets/142524952/58eae7c0-b3ce-4932-897f-763722d75ff6)

This page serves as a "home" page for the site! It shares a navbar at the top with all other pages to provide optimal usability. The page features a prominent button to direct users towards the route planning application. It gives brief breakdowns of relevant applications of the site and why it should be used.

## [Route Planner Page](/TruckingProject/Pages/RoutePlanner.cshtml)

![image](https://github.com/jmklr/TruckingSite/assets/142524952/4130fbab-c015-4ac9-b9df-9685dfb2ce21)

secondpage.html will be used for the route planning application. The name is entirely tentative. The page is very bare bones at the moment, with it's only true functionality being using JavaScript to find the latitude and longitude of the user and outputting it into a table. 

## [User Sign-Up Page](/TruckingProject/Pages/SignUp.cshtml)

![image](https://github.com/jmklr/TruckingSite/assets/142524952/ef4ade78-8d91-495f-9b9e-a6779a972153)

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

# Future Enhancements

## Main Page

The main page will likely see many enhancements in the near future. The main page, as well as every other page on the site, will feature a functional search bar in the navbar. The Main Page could include many new features in the future, including, but not limited to, a preview of the route planning functionality, recent routes, climate in popular destinations, or relevant news.

## Route Planning Page

The route planning page will be expanded upon the most in the future. Future developments will include features like a map, reverse geolocation, plotting routes, and changing route options. All of these features and more will combine to make a fully functional route planning tool.

## Signup Page

This page will likely either be developed to be fully functional or converted into a page where users can create accounts for the site.

## Future Pages

Many future pages will be included. Some ideas for future pages include a page fully dedicated to displaying relevant climate data, a page that features popular stops, and a page that shows previous routes.

# Citations

Bootstrap Buttons: https://www.w3schools.com/bootstrap5/tryit.asp?filename=trybs_button_styles&stacked=h

Color Palette: https://universityrelations.wvu.edu/brand-guide/color

E-Mail Form Idea: https://www.w3schools.com/bootstrap5/bootstrap_forms.php

JavaScript Geolocation Idea and Script: https://www.w3schools.com/js/js_api_geolocation.asp

NavBar Idea and Some Lines of Code: https://www.w3schools.com/css/css_navbar.asp

https://github.com/joshuatmeadows/MIST353ClassExample

https://github.com/joshuatmeadows/MIST353-TravelSite

# Reflection on Resources

Code used as an example in-class provided a very strong foundation for building the site, but didn't go further than the basics. This was beneficial as it gave me a lot of creative liberty and didn't make me feel boxed-in when developing my idea or the initial code. W3Schools provided a lot of interactive tools that helped build on the foundation I created using course materials. Many of my ideas were built on tutorials provided on the W3 site. I think this is a tool I'll use extensively throughout the development of this site and future individual projects. There were some difficulties with syntax in these tutorials, but some basic troubleshooting fixed these issues. Overall, information gathering was smooth with the exception of GitHub repos, as most people aren't going to create a tool that is already a part of many sites such as Google Maps or Mapquest. 
