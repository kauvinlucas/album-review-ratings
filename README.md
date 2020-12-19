<h1>Album ratings dataset</h1> 

[![GPL license](https://img.shields.io/badge/License-GPL-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

### What is this?
This repository cointains a dataset of the album's critic, user ratings and album data from two different music aggregators: Album of the Year (albumoftheyear.org) and Metacritic (metacritic.com).

A music review aggregator is a system that collects critic and user reviews of albums released by contemporary artists. These systems usually show album information and scores that allows music customers to compare different album releases or artists. Some websites also feed its users with information about the new releases.

### What kind of data it contains?
The Album Ratings data contains more than 30.000 rows of album metadata attributes (tags) such as release date, label and genre, along with the aggregated critic review scores and aggregated user review scores retrieved from the websites.

The Review Excerpts data contains more than 166.000 critic review excerpts extracted from Metacritic. Lyrics are not included in the dataset.

Scores aren't normalized:

* Album of the Year user and critic review scores, and Metacritic critic review scores range from 1 to 100.
* Metacritic user review scores range from 0.1 to 10.

### What can I do with this dataset?
This dataset can be used for EDA or to make album ratings predictions.

### How long did this scrapping project take?
The scrapping project started in October 7 2020 and took around 2 months to be concluded. 
It's expected to be upgraded periodically to include new album releases.
More sources are expected to be included.

### Are there any limitations in the data?
Before using this data, please keep in mind the following limitations:

* Compilation, reissue, single, live, mix, instrumental, audio book, bootleg, box set, demo, soundtrack and cover albums were excluded from the dataset.
* Metacritic only includes albums released from 1999 to present. Some albums released earlier than 2013 may also be missing.
* The data was gathered manually since the use of crawling scripts in this kind of websites is highly discouraged or disallowed.

### External links:
* This dataset in Kaggle: https://www.kaggle.com/kauvinlucas/30000-albums-aggregated-review-ratings
