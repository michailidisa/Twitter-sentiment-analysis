# Twitter-sentiment-analysis
Your task is to select 3-4 competitive product/service/current affairs/news categories (e.g. football/basketball/volleyball or theater/movies/tv, java/python/R etc.) and measure the public’s sentiment comparatively over a period of time (e.g. one month), in one or more countries.

1. Extract at least 1000 tweets for the categories you chose.
	- a. If you pick known names/brands etc. make sure they are not partisan/religious or other
	sensitive issues; you may pick however general issues such as Brexit or unemployment.
	- b. You will have to create a twitter developer account and get your own API key.
	- c. You should store them in a database table (e.g. MySQL)
	- d. You should include the following information:
		- i. User account (e.g. @berberidis)
		- ii. Number of account’s followers
		- iii. Number of account’s tweets
		- iv. Number of accounts retweets
		- v. Tweet text
		- vi. Date
		- vii. Location
		- viii. Hashtags
	-e. You can use regular expressions to clean the tweets from URLs, mentions. You can also get rid of tweets that only contain a URL or just mentions or they only retweet (which is the case often for bots), etc.
2. Classify them as negative/neutral/positive.
	- a. You can use TextBlob or any other off-the-self python sentiment classifier appropriate
	for this task. TextBlob (and others) provide pre-trained models so you don’t have to
	train the classifier yourself; you just have to use it for the classification of the tweets.
	- b. Store the sentiment in a field in your database
3. Plot the results in meaningful graphs; not just positive/negative tweet count, show how it changes over time. You may also weigh them according to user’s influence (i.e. number of followers, favs etc.). Improvise and be creative.
4. Your deliverable will be a zip file including:
	- a. Your source code in python. Include comments that explain what each function or block
	of code does. Don’t get into much detail though, focus on the most important parts.
	- b. Your database (dump SQL script)
	- c. A 5 pages (max) report that presents your methodology and findings.
		- i. Title
		- ii. Introduction
		- iii. Methodology iv. Results
		- v. Discussion-Findings
	- d. Your submission should be 1 file, named “Surname1-Surname2.zip”
