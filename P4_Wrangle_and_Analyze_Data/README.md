# P4: Wrangle and Analyze Twitter Data using Twitter API

**Summary**

In this project, we are using the dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. **WeRateDogs** is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

The archive "**Twitter-archive-enhanced.csv**" contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

The goal is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.

**Additional Data via the Twitter API**:  retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered by anyone from Twitter's API.

**Image Predictions File**: One more cool thing: I ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs*. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).


**Libraries to be installed**
- pandas
- NumPy
- requests
- tweepy
- json

## Summary of the findings

- Golden Retriever is the most rated dog breed followed by the Labrador retriever.
- Cooper, Oliver and Charlie are the frequently used dog names.
- Retweets vs Favourite Count: We see a positive co-relation between them. The more a post is retweeted, the more favourite counts or the more favourites the post recieves.
- We see almost half of the tweets(49%) were written in 2015 followed by 34% in 2016 and 18% in 2017.
- The most commonly used source to write the tweets is iPhone with 98% compared to Twitter Web Client and TweetDeck.
- Dogs in the "pupper" stage is the most available as compared to other stages.
- A Rating of 12 is most frequently given to the dogs followed by 10 and 11.