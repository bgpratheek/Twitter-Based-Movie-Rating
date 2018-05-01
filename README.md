# Twitter-Based-Movie-Rating
With microblogging platforms such as Twitter generating huge amounts  of textual data every day, the possibilities of knowledge discovery through Twitter data becomes increasingly relevant. Similar to the public voting mechanism on websites such as the Internet Movie Database (IMDb) that aggregates movies ratings, Twitter content contains reflections of public opinion about movies. This study aims to explore the use of Twitter content as textual data for predicting the entertainment rating. In this study, we will be extracting tweets from the Twitter API and predict the sentiment involved.Each tweet that we extract from the twitter should be categorized as a positive or negative tweet. We calculate the rating by the total of positive tweets by the total number of tweets.Results will be showing rating developed by our application is compared to IMDB and Rotten Tomatoes.



Steps for Running this project:
Necessary python packages that need to be installed in the machine.
1.tweepy
2.mysqlclient
3.IMDbPY
4.nltk
5.textblob
6.jsonpickle
7.bokeh
8.pickleshare
9.scikit-learn
10.numpy
If these modules are not present, here is the installation guide for having all the packages in the machine.

Installation:
pip install tweepy
pip install mysqlclient
pip install IMDbPY
pip install nltk
pip install textblob
pip install jsonpickle
pip install bokeh
pip install pickleshare
pip install scikit-learn
pip install numpy

Twitter tokens that needs to be added.
Modify the properties file with your tokens to access through your tweeter.
Tokens Needed:
token:
token_secret:
consumer_key:
consumer_secret:

Steps In running the project
1. Training the classifier with the Positive and Negative list of words.
cd Project
python3.6 Train_Classifiers.py


2. Database should be started:
create and install database and table using queries given in sql.db file.

3. Run the bokeh file.
bokeh serve --show myapp.py
this will open the browser window. 


4.In browser :
Enter the movie name to search and obtain the information.


Verify:
Check the information about the tweets and rating by checking in database table.
