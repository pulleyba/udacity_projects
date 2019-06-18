
# Project: Data Wrangling with Twitter
## by: Brice Pulley

### Introduction
> This project explores the data wrangling process which includes gathering, assessing, and cleaning the data. A brief analysis with visualizations followed the data wrangling process.

### Files
* image_pred - folder
    * `image-predictions.tsv` - dataset downloaded programmatically from Udacity servers. (**image_pred**)
* `tweet_json.txt` - file created from tweet extraction. (**tweet_count**)
* `master.csv` - the master file created after data wrangling from separate sources. (master)
* `twitter-archive-enhanced-2.csv` - dataset of tweet information for 'WeRateDogs'. (**archive**)
* `act_report` - summary of analysis after data wrangling
* `wrangle_report` - summary of data wrangling efforts for project

### Datasets
> `archive` - provided by Udacity that is an archived dataset of tweets from 'WeRateDogs' (@dog_rates) twitter account from 08/01/2017 and before. Columns include:
   * tweet_id
   * timestamp
   * source
   * text
   * rating_numerator
   * rating_denominator
   * name
   * etc...

> `image_pred` - dataset of the results of image prediction. The archive table ran through a neural network to classify breeds of dogs and predict them. Columns include:
   * __tweet_id__ - id number
   * __jpg_url__ - link to image
   * __img_num__ - which image per tweet (1-4)
   * __p1, p2, p3__ - predictions for dogs (1ST, 2ND, 3RD)
   * __p1_conf, p2_conf, p3_conf__ - confidence for each prediction
   * __p1_dog, p2_dog, p3_dog__ - whether prediction is TRUE or FALSE.
   
> `tweet_count` - dataset created programmatically extracting data through twitters API using tweepy. Columns include:
   * tweet_id
   * retweet_count
   * favorite_count
   
### Software Required
> Standard installation of anaconda 3 for data science.
* Python 3.73.3
* Pandas 0.24.2
* NumPy 1.16.2
* Seaborn 0.9.0
* matplotlib 3.0.3

> * tweepy - https://github.com/tweepy/tweepy
* word_cloud - https://github.com/amueller/word_cloud

### Sources
* Udacity
* Twitter `WeRateDogs` @dog_rates
* World Cloud
* Tweepy


```python

```
