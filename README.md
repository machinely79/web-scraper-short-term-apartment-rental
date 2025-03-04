# Web Scraper – Short-Term Apartment Rentals

This project is a web scraper built with ```Selenium``` and ```undetected-chromedriver``` to extract short-term apartment rental data from OLX.ba. It navigates through multiple pages, collects ad details, and saves the data into a CSV file for further analysis.

Features

  Resumes from the last scraped page to avoid redundant scraping.
  Avoids duplicate listings by checking already saved links.
  Extracts key rental information, including title, price, description, and additional details.
  Implements scrolling and retry mechanisms to improve data collection.
  Saves data in CSV format, making it easy for further analysis.
