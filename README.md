# airbnb-Seatle
# Table of content
1. [Installation](#Installation)
2. [Motivation](#Motivation)
3. [File Description](#FileDescription)
4. [Results](#Results)
5. [Acknowledgements](#Acknowledgements)

<a name="Installation"></a>
# Installation

One need Anaconda distribution of python 3.* version. There is no need of any additional libraries for this project because Anaconda has all the required libraries.

<a name="Motivation"></a>
# Motivation

This project is the First Project of Data Scientist Nanodegree Program from Udacity. The goal of the project is to implement the CRISP-DM (Cross-Industry Standard Process for DATA Mining). One can use his own datasets or the datasets provided at the 'Project Motivation and Details' Description.
I have decided to use the Seattle Airbnb dataset to get some useful insights. Following are the 3 questions I have looked in this dataset.

1. How Price is affecting the number of beds, bedrooms and bathrooms that can be in a Hotel
2. Best time to visit Seattle and Availability of room and early planning for the trip
3. Who are among the popular neighbourhood 

<a name="FileDescription"></a>
# File Description

There is one jupyter notebook file that answers the above questions. This file includes all the step done to answer these question.

**Seattle_airbnb_CRISP_project.ipynb**


There are three datasets files in Seattle Airbnb dataset that can be downloaded from Kaggle (https://www.kaggle.com/airbnb/seattle)

* **listings.csv:** including full descriptions and average review score
* **reviews.csv:** including unique id for each reviewer and detailed comments
* **calendar.csv:** including listing id and the price and availability for that day

<a name="Results"></a>
# Results

Followings are the key findings:

* There is a general tendency that a hotel having more no of beds are charging more money 
* Most rooms are available in the month of December, March etc which mean less people are visiting Seattle during this time whereas a large no of reviews in the month of August, July and September indicates People are visiting Seattle during this time of the year.
* Excluding "Other Neighbourhoods", most popular neighbourhoods are Downtown, Capital Hill and Central Area

One can find more in my [blog](https://medium.com/@mansuri4638/my-first-story-seattle-airbnb-26cac2524ab5?sk=379482f15e85882651440cb0162d25d9)

<a name="Acknowledgements"></a>
# Acknowledgements
This dataset is part of Airbnb Inside, and the original source can be found [here](https://www.kaggle.com/airbnb/seattle)
