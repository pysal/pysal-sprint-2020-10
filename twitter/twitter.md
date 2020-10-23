# information flow
1) from PySAL/CGS website: news_item.md > rss feed > consumed/translated into tweet.
    -initial goal is to have a script that consumes a [.md file with specific front matter format](esda_2.0.0.md) and translate it into an item for an RSS feed, which will in turn become a tweet.
    is an RSS feed necessary? can we use a single RSS feed for two separate websites?

2) from google scholar: can set up google scholar alerts for keywords, such as PySAL. These send an email whenever a paper containing the keyword(s) is uploaded. We can leverage these emails to extract information about projects using PySAL. 

3) from github: ???

We can use the twitter API to coordinate several information feeds onto a central twitter account from which any news about package releases, paper highlights, or work from PySAL developers can be read.

# tweepy functionality
[installation](http://docs.tweepy.org/en/v3.9.0/install.html)

Using tweepy, we can write scripts to do practically any interaction avilable on twitter. Notably, we can:

    1) compose and send tweets
    2) like and retweet other tweets 
    3) search for and follow accounts

When combined with python, we can leverage outside information (files) to process PySAL/CGS information/news into tweet format and drive engagement for the PySAL community.