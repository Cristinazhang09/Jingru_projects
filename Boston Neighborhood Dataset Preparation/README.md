# Project Name: Boston Neighborhood Dataset Preparation
The purpose of the project is to provide valuable information for potential house purchasers in the city of Boston, based on their potential budget, safety concerns, and the needs for the type of life, such as if one likes jogging or walking, a house has trails nearby would be a good choice, and if one is a big fan of movies, nearby cinema would be of interest. 

## Installation
The code requires Python versions of 3.* and general libraries.

## Project Motivation and Description
In this project, I used three data sources, the first one is the Boston crime incident report dataset available at data.boston.gov, in which crime incidents with the location of the crime happened, time, and severity of the crime etc. are included in the dataset; the second one is the house price data I scraped from zillow.com, which has the information of the geographic location of the houses, the price, number of bathrooms, number of bedrooms, the size of the houses, etc., the third data is from the Foursquares API, where I used the house location to find the nearby venues, such as cinemas, restaurants, trails, parks, museums, etc. The three data sources are connected with each through the geographic information for the houses, venues and crime incidents.

## Results
Finally, I put together a Boston's house information data set with the house prize, house location (latitude, longitude), number of bedrooms, bathrooms, size, nearby number of different venues, and the number of crime incidents occured from August, 2015 to now. This dataset could be used to help both agents and purchasers to either sell a house to a customer or find a dream house.
