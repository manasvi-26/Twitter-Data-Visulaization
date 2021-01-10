# Twitter Data Analysis and Visualization:
### Hashtag Used : #INDvsAUS
#### Go to `Dash.pdf` to view the visualizations. 
#### Files:
##### Json Files:
- `Tweets.json` :
The Tweets were Collected using ‘Twint’ through the command line.
Command Used:
twint -s "#INDvsAUSTest" -o tweets.json --hashtags --limit 20000 --json 
Contains twint tweet type objects
Approximately 20K tweets were loaded into the file.
Referenced Link: https://github.com/twintproject/twint/wiki
- `User.json`:
User data was collected using the tweepy API.
Approximately 6k users’ data was loaded into the file
Contains User tweepy objects
Referenced Link: http://docs.tweepy.org/en/latest/
- `MostLiked.json`:
Stores the information about the users of the top 10 most like tweets.
Contains User tweepy objects

##### Python Notebooks:
- `Visualization_task2.ipynb`:
View the Graphs in Dash.pdf
Code involves visualizing the data collected from tweets.json and user_data.json.
Used the Plotly module along with Dash web application to make interactive visualizations.
Referenced link : https://plotly.com/python/
	
- `User_data.ipynb`:
Code involves collecting user data using the tweepy API.
Collected list of Users from tweets.json file and then called the api to get further information wrt each user.
Referenced Link: http://docs.tweepy.org/en/latest/




