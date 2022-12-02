# task
scraping some texts from web-sites.
The help of requests, beautifulsoup and pandas we can scrape any info from web-sites to our dataset. To make large and useful datasets, scraping can help us. In that example project, I coded the scraper-functions which are specialized to scrape texts in <p></p> tag from articles, namely, I collected data from kun.uz.
1.Those functions I just created, we can automate our process so that we can get new data everyday, I mean, we connect it with FastAPI, and and just with copying url-link, we can exactly achieve what we want. It might return us data as json.
2.I'd prefer to store our data into excel spreadsheets or json files, couse, these formats are more useful for data science than others in my view. But sql tables are also confidential to save our data
3.I think, to evluate our collected text-data, we can use nltk as text-generator and to find something necessary from text in order to use in purpose.
