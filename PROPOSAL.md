# <center>Sydney Suburbs and Beaches: A Study </center>

<center>Lukman</center>


## Introduction
The sun shining, cold beers, warm water, surfers enjoying the waves, a lot of fun and many other wonderful things. Sydney is famous around the world for its beaches. There a lot of beaches in Sydney, from the most popular Bondi beach to the hidden and secret like Resolute beach. Everyone wants to feel and experience Sydney beaches. It is a dream for most of people to live in a nice house near beaches. From data science perspective, it raises question. Is it possible to predict whether a location is near beach or not?

<a data-flickr-embed="true" href="https://www.flickr.com/photos/130650084@N03/31986050271/in/photolist-QJuSnn-oGg2Gv-aEiq2t-2VTixH-FJzhJq-JUTZPY-ThzkLp-28TZwi-YoqKnt-zH4d3-68yrrQ-21sNvAs-Cy5AkN-rtWjca-3bZzCa-aEneDw-7hg9H-Cy5AEf-NdYxCk-FsuwVY-X3bHsb-aR9f2H-bw1YGG-26yAHhQ-PzTTU8-8fpqJY-PTcaMB-FfTtft-7z9mXt-4YRJWM-29yxR3Q-e5NBPy-DGqWa7-9uxKn9-6nSfw8-2dSVqrF-dtqy-NZj8Dg-sFky-PzTQrX-T5tbXA-FC1A58-CJXg4S-sFkJ-3iVwu7-NW5dWh-T62kY9-NZj8Gx-sFk6-N2tY5w" title="Sydney"><img src="https://live.staticflickr.com/574/31986050271_72cbc2113b_k.jpg" width="1900" height="1187" alt="Sydney"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

## Goal

In this project, we want to find the answer to the following question: 
Given data that is not geographical, is it possible to predict whether a location, in this case a suburb is near beach or not?

## Dataset
In this project, we use several tables from Australian Bureau of Statistics 2016 census. Every table’s rows consist of suburbs in Sydney. The tables are:
1. Cultural Diversity, counting persons, 10 years age group
2. Cultural Diversity, counting persons, total personal income (weekly) 
3. Employment, Income and Education, counting persons, distance to work
4. Employment, Income and Education, counting persons, education level
5. Selected Dwelling Characteristics, counting dwellings, rent (weekly)
6. Selected Dwelling Characteristics, counting dwellings, number of motor vehicles
7. Selected Family Characteristics, counting families, count of children

Initial exploration of the datasets showed that the datasets, in this case the tables, are good and complete. Every table has same 283 number of rows consisting of every suburb in Sydney.


## Analysis Techniques
The predicting models that are used in this project are Logistic Regression, K-Nearest Neighbour and Support Vector Machine. Initially, all the tables in the dataset and all the features in the tables are used to train the models, after that only tables and features that contribute significantly to the accuracy of the model are used.
* Milestone 1
Train all the models using all available datasets and evaluate the accuracy.
* Milestone 2
Improve the models accuracy with additional data.

## Photo Credits
[1] “Bondi Beach” Photo by [FRANCOIS VEQUAUD](https://www.flickr.com/people/130650084@N03/) on Flickr
