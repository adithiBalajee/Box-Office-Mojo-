# Box-Office-Mojo-
## Purpose of this project
A data analysis project that scrapes and visualizes U.S. weekend box office trends (2020–2024) using data from Box Office Mojo. Includes web scraping, data cleaning, and visual answers to highlight patterns in revenue and release data.
This project uses data scraped from [Box Office Mojo](https://www.boxofficemojo.com/weekend/by-year/) to explore trends in U.S. weekend movie performance from 2020 to 2024.

## Project Basis
- Scrapes data from **multiple pages** (one per year, 2020-2024)
- Cleans and organizes the dataset
- Analyzes trends using **pandas** and **seaborn**
- Answers 4 questions about the data (see notebook)

## Analysis Questions considered in the study
- Which year had the highest total weekend revenue?
- Which movie had the top-grossing opening weekend per year?
- How do grosses change seasonally?
- Which months have the most releases? 

## Files included in the repositoy
- `box_office_mojo_webscrape.ipynb`: Full scraping + analysis notebook
- `cleaned_box_office_data.csv`: Cleaned dataset
- `box_office_weekend_data.csv` : Original dataset from scraped website (uncleaned)

## Source
Scraped from: https://www.boxofficemojo.com/weekend/by-year/
