# Py_Scrap



# Twitter Hashtag crawler

git clone https://github.com/amitupreti/Hands-on-WebScraping

cd Hands-on-WebScraping/project1_twitter_hashtag_crawler

pip install -r requirements.txt --user


Put the hashtags in a csv file seperated by new line in `myhashtags.csv` 


2. Run the crawler
    scrapy crawl twittercrawler -a filename=myhashtags.csv -o mydata.csv
