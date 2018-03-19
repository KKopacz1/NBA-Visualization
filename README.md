
## Web-scraping the "basketball-reference" website to get the NBA college stats for NBA players

### Pre-requisites:
 
* The nba db  should be created in the mongodb with the collection - nba_bio and all the players data.

### To Run this File-

* Start the mongodb server in the console. 
* Run this file to scrape the web for all the players in the nba_bio collection in nba database. 
* The result is a collection - nba_collg in the nba database with the data scraped.

### Exception Handling:
 
* The 'G' key of the college_stats dictionary shows 'NA' when there is no college stats data available for a player. 


