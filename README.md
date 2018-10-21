# Airbnb
Exploration of data from Airbnb.

## Installation
### Libraries
I've mainly used standard python libraries such ```numpy, pandas & math``` throughout the project. I've also used ```matplotlib & seaborn``` for plotting as well as ```os, json & folium``` for creating choropleth maps.

### Data
The data set used in this project is publicly available at:
- http://insideairbnb.com/get-the-data.html

## Motivation
The initial motivation for this project came from my Data Scientist Nanodegree Program at Udacity. Becoming a data scientist does not only mean learning how to build fancy machine learning models, but also how to communicate results. Whether it's an analysis you've made, a model you've built or a software you've programmed, your work will be useless unless the people you work with are able to understand what's going on.

In order to practice my communication skills I've decided to answer three questions around an Airbnb data set while using GitHub for end-to-end project documentation as well as a Medium blog post for presenting the results. As I am German I've decided to use data of Airbnb listings from Berlin. The three questions I was interested in were:
* What are the most popular Airbnb locations in Berlin?
* How much money can you make with Airbnb apartment in Berlin?
* What factors influence the income of an Airbnb apartment in Berlin?

While answering the questions above I tried to stick to the CRISP-DM process.

## Files
The following notebooks from the _notebooks_ folder were used throughout the analysis of the data set:
```
- q1_airbnb_popularity.ipynb
- q2_airbnb_income.ipynb
- q3_airbnb_income_features.ipynb
```
The notebooks include the code to answer all three questions as well as markdown cells that outline the underlying thought process and a discussion of the obtained results. The folder _data_ includes a ```.geojson object that was used to draw a choropleth map of Berlin neighbourhood groups:
```
- berlin_neighbourhood_groups.geojson
```
Last but not least, the folder _results_ contains three graphical outputs of the analysis (one for each question) which were used to present the findings of this project in a Medium blog post:
```
- airbnb_income_neighbourhoods.html
- correlations.png
- popularity.png
```

## Findings

## Acknowledgements
I'd like to thank http://insideairbnb.com for providing the data for public use (following the link provides additional descriptions regarding the data set as well as licensing information). Also, I'd like to thank https://www.technologiestiftung-berlin.de/ for providing the ```.geojson```object used to draw the choropleth map of Berlin neighbourhood groups.
