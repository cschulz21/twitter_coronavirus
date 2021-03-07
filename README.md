# Coronavirus analysis

The aim of this repo is to monitor the spread of coronavirus on social media. The data used is all geotagged tweets from 2020. I tracked both the language the tweet was sent in as well as the country where the tweet originated. 

Because the data set is so large, the tweets were partitioned by the day they were sent. I then mapped and reduced them to get summaries on the whole data set. All of the information from the reduction can be found in `reduced.country` and `reduced.lang`. 

To visualize each hashtag tracked, I have separated the hashtags and country/language. For each hashtag there is a `.country` and `.lang` file within the `viz` or visualization folder.
