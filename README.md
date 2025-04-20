# Box Office Mojo – Web Scraping and Analysis of U.S. Weekend Box Office Trends (2020–2024)

## Purpose of the Project

The purpose of this project is to collect and analyze weekend box office data from the United States across the years 2020 to 2024. The data was scraped from the website [Box Office Mojo](https://www.boxofficemojo.com/weekend/by-year/) using a Python-based web scraping pipeline built with the `requests` and `BeautifulSoup` libraries.

This project is designed to apply practical data science skills, including web scraping, data cleaning, exploratory data analysis, and visualization. The goal is to answer real-world questions about trends in movie releases and revenues using scraped data structured into a pandas DataFrame.

The analysis explores questions such as:
- Which year had the highest total weekend box office revenue?
- Which movie had the highest-grossing opening weekend each year?
- How do weekend grosses change seasonally (e.g., summer vs. winter)?
- Which months have the highest concentration of movie releases?

Each of these questions was answered programmatically, and visualized using the `seaborn` library. Visualizations include custom formatting, data labels, and clear titles to highlight findings.

---

## Files Included in the Repository

- **`box_office_mojo_webscrape.ipynb`**: The main Jupyter Notebook containing all code for scraping, cleaning, analysis, and plotting. Markdown cells are used throughout the notebook to organize content and explain each step. All code is commented.
- **`box_office_weekend_data.csv`**: The raw dataset obtained from the web scraping process.
- **`cleaned_box_office_data.csv`**: A cleaned version of the dataset that separates holiday/event labels from the weekend dates.
- **`README.md`**: This file, which explains the project structure, its goals, and the contents of the repository.

---

## Data Source

The data was scraped from Box Office Mojo’s weekend box office archive:  
**https://www.boxofficemojo.com/weekend/by-year/**
