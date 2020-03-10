# Airbnb
Exploration of data from Airbnb.

## Installation
### Libraries
I've mainly used standard python libraries such ```numpy, pandas & math``` throughout the project. I've also used ```matplotlib & seaborn``` for plotting as well as ```os, json & folium``` for creating choropleth maps.

### Data
The data set used in this project is publicly available at:
- http://insideairbnb.com/get-the-data.html

## Motivation
Whether it's an analysis made, a model built or a software programmed, your work will be useless unless the people you work with understand what you've done. Parts of my Data Scientist Nanodegree programm at [Udacity](https://eu.udacity.com) were about practicing communication skills thus I've decided to do so by answering three questions around an Airbnb data set while using GitHub for end-to-end project documentation as well as a Medium blog post for presenting the results. Being German I've decided to use data of Airbnb listings from Berlin. The three questions I was interested in were:
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
The notebooks include the code to answer all three questions as well as markdown cells that outline the underlying thought process and a discussion of the obtained results. The folder _data_ includes a ```.geojson``` object that was used to draw a choropleth map of Berlin districts (in the data set referred to as neighbourhood groups):
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
Out of 12 districts in Berlin, _Mitte_ appears to be the most popular one by far. With on average _$ 115 per month_ this district, located in the heart of Berlin, is also among the top four in terms of income one can make by renting out an apartment on Airbnb. The only other district in which apartments make more money is _Marzahn-Hellersdorf_ with _$ 126 per month_. Despite obvious influencing factors on an apartment's monthly income I could find weak positive correlations with the _apartment size_ as well as _superhost status_ of an Airbnb host.

For more detailed findings please refer to the _notebooks_ folder and [this](https://medium.com/@patrickpeltier/renting-out-your-apartment-in-berlin-3c7a6d685392) Medium blog post.

## Acknowledgements
This mini project was one of the projects I've worked on during my Data Scientist Nanodegree programm at [Udacity](https://eu.udacity.com). It was mainly fueled by publicly available data at http://insideairbnb.com (following the link provides additional descriptions regarding the data set as well as licensing information). Also, the ```.geojson```object used to draw the choropleth map of Berlin districts was provided by https://www.technologiestiftung-berlin.de/.
