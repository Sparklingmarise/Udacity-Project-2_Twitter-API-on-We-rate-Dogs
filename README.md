
# Twitter API Assessment

In this assessment, three different datasets of various formats (csv, tsv, and json text file) were used

# Importing packages 


```python
import pandas as pd
import json
import configparser as configparser
from urllib.request import urlretrieve
import requests
import io
import requests
import numpy as np
import tweepy as tw
import seaborn as sb
import matplotlib.pyplot as plt
%matplotlib inline
```

# Introduction

The tweet history of Twitter user @dog rates, otherwise known as WeRateDogs, is a dataset that will only be very useful for various purposes only when properly wrangled. Applying the knowledge from python and its libraries, we can make the cleaning of these data.

In the sections below, first, all the three pieces of data for this project are gathered and loaded into Jupyter notebook using appropriate methods required to gather each data. Secondly, data assessment is a critical aspect of data wrangling process. By this assessment, whether by visual or done programmatically, are critical for identifying data quality and tidy issues for documentation.

In the cleaning section, all the issues documented while assessing were cleaned after a copy of the original data was made. Cleaning includes merging individual pieces of data according to the rules of tidy data. Then the result, which a better-quality and tidy master_data pandas DataFrame (or DataFrame) were stored.

Furthermore, the analysis and visuals of the wrangled data was made to give detailed insight that can be applied by companies that provides goods and services for the promotion of their products such as dog food and accessories sales, and healthcare services. When such opportunities are maximized and products well marketed on Twitter at such time, there is a probability of increased sales and possibly income.


## Questions for the insights
1. In the WeRateDog data collected, the tweets for how many years were recorded in the data collected? Which year has the highest tweet?

2. Which month(s) has the highest tweet of year? 

3. Considering the three years data, which month had the highest tweet value counts?


# Findings

- There are records for about three years. The year 2016 has the highest number of tweets across the three years.

- It was observed that the value count for the year 2015 is 66. However, this record was for only for the twelfth (12th) month.

- The observation here is that the first month has the highest record of tweets. This can be attributed to the season of love that is an extension from the Christmas season and holiday coupled with the cold in some countries.

- During this time, family, and friend (and by extension pets such as dogs) are shown some care and love. 

- Secondly, during this holiday season, friends and family spend quality time with each other, and that includes their dogs. 

- At this period, lots of tweets about dogs are recorded on Twitter page. It is important that companies involved in dog foods, accessories, products, and healthcare can maximize such opportunities to do a huge promo on their products because many dog owners have the time and pay more attention to them.

- Also, the love and care during this season may be extended to their pets that can be demonstrated by treating their dogs with new product or in a special way.

- Although the data for the year 2017 is incomplete, the month of January also showed the highest number of tweets. This be used to buttress my insight as stated for the year 2016.



```python

```


```python

```
