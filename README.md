# Module 11 - Web Scraping challenge: Mars Analysis

## Overview

This project reviews Mars news articles and the weather patterns observed by the Mar's Curiosity rover.
The files are:
+ *part_1_mars_news*
+ *part_2_mars_weather*

---

## Deliverables

### Part 1: Scraping Mars News

- Automated browsing using Splinter to visit the Mars News site.
- HTML parsing with BeautifulSoup to extract:
  - Article titles
  - Article preview text
- Each article is stored as a dictionary with `title` and `preview`.
- Final output is a list of dictionaries for all articles.

### Part 2: Scraping Mars Weather and Analysis

- Scraped Mars weather data from an HTML table hosted online.
- Parsed and cleaned the data using BeautifulSoup and Pandas.
- Converted columns to their correct data types.
- Performed the following analyses:
  - Number of unique Martian months
  - Number of sols (Martian days)
  - Average minimum temperature by month
  - Average atmospheric pressure by month
  - Estimated the number of Earth days in a Martian year

- Visualizations created using Matplotlib:
  - Minimum temperature by month
  - Atmospheric pressure by month
  - Daily minimum temperature over Earth time

- Exported dataset to CSV: `mars_weather_data.csv`

## Technologies Used

- Python & Jupyter Notebook
- Splinter (browser automation)
- BeautifulSoup (HTML parsing)
- Pandas (data manipulation)
- Matplotlib (visualizations)
