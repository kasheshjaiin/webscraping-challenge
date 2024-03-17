# Mars Data Analysis

## Introduction
This repository contains code for scraping and analyzing data related to Mars. The project consists of two main parts:

1. **Part 1: Scraping Mars News**
   - In this part, we scrape titles and preview text from Mars news articles using web scraping techniques.
   - We utilize automated browsing with Splinter and HTML parsing with BeautifulSoup to extract information from the Mars News website.
   - The scraped data is stored in Python data structures and optionally exported to a JSON file for easy sharing.

2. **Part 2: Analyzing Mars Weather Data**
   - This part involves scraping and analyzing Mars weather data, which exists in a table format.
   - We use BeautifulSoup to scrape the data from the Mars Temperature Data Site.
   - The scraped data is assembled into a Pandas DataFrame and analyzed to answer various questions about Mars weather.
   - Key analyses include determining the number of months on Mars, identifying the coldest and warmest months, and estimating the number of terrestrial days in a Martian year.

## Technologies Used
- Python
- Splinter
- BeautifulSoup
- Pandas
- Matplotlib
