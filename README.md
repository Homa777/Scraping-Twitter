# Scraping-Twitter
Scraping Twitter without twitter API

Twitter has introduced changes to their API that have rendered various tweet-scraping libraries obsolete. Luckily snscrape, as a library that allowed me to scrape tweets without the restrictions of Tweepy (Twitter API).

Recently, I had to scrape twitter website to make a dataset using comments of users in twitter. Unfortunately, I could not access to key token and password by twitter API. I did not have enough time to wait to get those mentioned credentials by twitter API. I applied for twitter as develpoer to get key token, but it took a lot time to get back to me. Therefore I use twint library which end up with no plausible results. It seems twitter no longer let users to use Twint library to scrape it. 

Therefore, I searched and found SNScrape (A scraper for social networking platforms known as snscrape (SNS). It retrieves objects, such as pertinent posts, by scraping things like user profiles, hashtags, or searches).

You can scrape twitter based on your requirements for example, you can define a search function which takes the inputs as arguments and creates a query string to be passed inside SNS twitter search scraper function. These inputs can include:

#Text 
#Username 
#Since 
#Until 
#Retweet 
#Replies 

 I used development version of Snscrape using following github repository. You need to install this through git. Please make sure you have installed git in your system.

The Python package dependencies are installed automatically when you install Snscrape. You can install using the following commands.

I used development version of Snscrape using following github repository. You need to install this through git.

pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git
