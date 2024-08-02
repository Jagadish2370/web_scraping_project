# JustWatch Movie and TV Show Scraper
### Project Description
This project is a web scraping tool designed to extract movie and TV show data from JustWatch (https://www.justwatch.com). It uses Python, BeautifulSoup, and requests to scrape information such as titles, release years, genres, IMDb ratings, and available streaming services. The scraped data is then analyzed using Pandas and exported to CSV files.
### Features
* Scrapes movie and TV show data from JustWatch
* *Extracts information including:*
  * Title
  * Release year
  * Genre
  * IMDb rating
  * Runtime/Duration
  * Age rating
  * Production country
  * Available streaming services
* Handles rate limiting and retries
* Performs data analysis on the scraped information
* Exports results to CSV files

### Requirements
* Python 3.x
* BeautifulSoup4
* Requests
* Pandas
* NumPy

### Data Analysis
The script performs the following analyses:

* Calculates average IMDb ratings for movies and TV shows
* Identifies top genres
* Determines the most prevalent streaming services


### Output
* The script generates two CSV files:

* final_data.csv: Contains all scraped and analyzed data
* filtered_data.csv: Contains data filtered based on specific criteria (e.g., recent releases, high ratings)

### Notes

* This project is for educational purposes only. Be sure to comply with JustWatch's terms of service and robots.txt file.
* The script includes delays to avoid overwhelming the target website. Please use responsibly.



