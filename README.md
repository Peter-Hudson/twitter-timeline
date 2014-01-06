Twitter Timeline Example
========================

A first attempt (will need some tweaks; as I am still learning) at using Dart on command-line to get your timeline updates from Twitter (using Twitter API version 1.1) and save to a JSON file. 

## Setup
#### Update config.json with:
1. "screen_name" - Twitter account username
2. "consumer_key" - Taken from when you create a Twitter App.
3. "consumer_secret" - Taken from when you create a Twitter App. 
4. "max_count" (optional) - currently set to 100, gets 100 Tweets at a time.  

### To Do:
1. Look at handling the updates.json file when it reaches a certain size, as this will cause problems in the future.
2. Update to use a database.