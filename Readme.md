
# Homework 3 - Group 1


<p align="center">
  <img width="460" height="300" src="https://www.3ders.org/images2016/airbnb-partners-matterport-launch-3d-virtual-tour-pilot-project-4.jpg">
</p>


This repository contains the results of the __Homework 3__ of Algorithmic Methods of Data Mining.
The collaborators of this homework were __Basso Mattias__, __Cantagallo Edoardo__ and __Machani Sreenivasalu Lohith__ .

### Data 
The databases used in this homework can be found [here](https://www.kaggle.com/PromptCloudHQ/airbnb-property-data-from-texas ).

It contains several informations about insertions of houses and apartments on Airbnb platform, all the building are located in Texas - US. 

## A brief introduction

As a result, we have a __Jupyter Notebook__ that contains all the work done, explained step by step and few links showing the maps requested by the bonus point.

The purpose of the homework was to build a __search engine__ able to retrieve information from 18 thousands documents regarding _airbnb insertions in the state of Texas - US_, considering as input a text query given by the user.

The search engine at first return _all the documents_ related to the apartments _that contain all the words in the query provided_; in further steps we had to return better results, taking into account the _tf-idf scores_ for the documents and combining them with the _cosine similarity_ as scoring function. 

Our creative approach then came in, as the final request was to think about a __new scoring function__ for our search engine. We decided (as with the informations we could retrieve from docs) to take into account _the distance by the city center of the house/apartment and the ratio between average price per night and number of bedrooms_. Normalizing those numbers we were finally able to achieve a different way to score our results.

We present also in this repository, the achievement of the "__Bonus__" point of the HW. We had to show, for a given place (namely or with coordinates) all the documents (buildings) in the db which are within a range (kmeters) from an adress. The markers upon the location in the map allow us to open the link of the related apartment.


### Maps

The links below show the maps for Dallas and San Antonio, which cannot be seen from the jupyter notebook uploaded.

https://nbviewer.jupyter.org/github/Edoardoba/Homework03/blob/master/dallas.html

https://nbviewer.jupyter.org/github/Edoardoba/Homework03/blob/master/san_antonio.html

