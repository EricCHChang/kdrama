# kdrama
Exploring an IMDb Korean Drama/Show Dataset: Foundation for a K-Drama Recommendation App

## Motivation

During the pandemic, I have more time staying at home so I need to find some new hobbies. One of them is watching Korean dramas (K-drama). I really enjoyed it; however, when I finished watching one drama, one thing that sometimes bothers me is that "What should I watch next?". Also, if I find one, how do I know if it is a good drama?

I am thinking it would be great if there is a K-Drama recommendation app that can recommend good dramas (ideally across all streaming platforms). To achieve this, a huge dataset containing many Korean dramas/shows and their information (e.g., user ratings, genre, cast, description, availabile on which streaming platform, etc.) will be required. 

I found an IMDb Korean TV Series dataset on Kaggle (https://www.kaggle.com/datasets/chanoncharuchinda/imdb-korean-tv-series?select=koreanTV.csv). The data was scrapped on December 11, 2021 by Chanon Charuchinda. It contains roughly 2,000 Korean dramas and TV shows, defined as those with "South Korea" in the country of origin, on the IMDb website. This dataset consists of various information of dramas/shows such as title, release year, user rating, genre, cast, synopsis, etc. Unfortunately, it does not have the information about online streaming platform. 

I decided to explore this dataset as a starting point. Specifically, I aim to identify features that are predictive of ratings of K-dramas/shows. In other words, I want to understand what features/information users should check when they look for good K-dramas/shows. Further, I plan to build a recommendation model by anlayzing the similarity of dramas/shows based on their synopses and other text information. Such a model will be beneficial for users to find out dramas/shows that are similar to a drama/show they like before. 

## Goals

- [x] Exploratory analyses of features/information in the dataset
- [x] Correlational analyses between ratings and other features  
- [x] Build a multiple linear regression model to predict ratings
- [ ] Content-based recommendation model



