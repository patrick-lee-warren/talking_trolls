# talking_trolls
Data repository to accompany "Talking to Trolls – How Users Respond to a Coordinated Information Operation and Why They’re So Supportive," Darren L. Linvill, Amanda Moore, and Patrick L. Warren

Three .csv files that, taken together, contain all the data for the paper. 

- troll_growth.zip
- unlabeled.zip
- labeled.zip

The variable defintions for each file are as follows:

-troll_growth.zip
  - filled_author (str) IRA troll screen name
  - account_type	(str) The type of troll mentions, using typology from Linvill & Warren (2020), available [here](https://github.com/patrick-lee-warren/IRA-Troll-Types). 
  - date (str) date at which stats were recorded
  -	follower_num (int) number of followers
  -	following_num (int) number of following
  - retweet_count (int) total retweets received by all tweets from this troll on this day
  
-unlabeled.zip
  - CONTENT (str) The textual content of the tweet mentioning an the IRA troll.
  - troll_mentioned  (str)  The screen name of the mentioned IRA troll
  - filled_atype2  (str) The type of troll mentions, using typology from Linvill & Warren (2020), available [here](https://github.com/patrick-lee-warren/IRA-Troll-Types).  
  - PUBLISH_DATE (str) Date and time tweet was published
  - POST_TYPE (str) Type of tweet, one of {QUOTE_TWEET, RETWEET, or NA (indicating original tweet)}

-labeled.zip
  - CONTENT (str) The textual content of the tweet mentioning an the IRA troll.
  - troll_mentioned  (str)  The screen name of the mentioned IRA troll
  - filled_atype2  (str) The type of troll mentions, using typology from Linvill & Warren (2020), available [here](https://github.com/patrick-lee-warren/IRA-Troll-Types).  
  - PUBLISH_DATE (str) Date and time tweet was published
  - POST_TYPE (str) Type of tweet. One of {QUOTE_TWEET, RETWEET, or NA (indicating original tweet)}
  - narrow_lab (str) Hand-coded label. One of {?, Attack, Comment, Support, Troll Whistle} 
 

