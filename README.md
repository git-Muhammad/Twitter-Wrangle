# Twitter-Wrangle

Project: Twitter-Wrangle

The dataset that will be wrangled, analyzing and visualizing is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.


## What Software Do I Need?

- You need to have a Jupyter Notebook software.
- The following packages (libraries) need to be installed:

   - pandas
   - NumPy
   - requests
   - tweepy
   - json

## Description of the files on the repository 

- wrangle_act.ipynb : Jupiter Notebook python code

- image-predictions.tsv : downloaded data programitally on wrangle_act.ipynb via URL
- image_predictions.csv : written csv file from image-predictions.tsv 

- tweetsAPI_json.txt : retrieved tweets data through Twitter API.
- RT&Likes.csv : written csv file from tweetsAPI_json.txt

- twitter-archive-enhanced.csv : given data set will be readied on wrangle_act.ipynb

- twitter_master.csv : combined cleaned dataset from image_predictions.csv, twitter-archive-enhanced.csv, RT&Likes.csv


### Report

- wrangle_report.pdf : a report of the wrangling process has been made.
- act_report.pdf :  a report of the final insights and observations from the dataset.

