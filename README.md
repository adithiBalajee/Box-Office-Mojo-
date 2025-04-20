# Box Office Mojo – Web Scraping and Analysis of U.S. Weekend Box Office Trends (2020–2024)

## Purpose of the Project

The purpose of this project is to collect and analyze weekend box office data from the United States across the years 2020 to 2024. The data was scraped from the website [Box Office Mojo](https://www.boxofficemojo.com/weekend/by-year/) using a Python-based web scraping pipeline built with the `requests` and `BeautifulSoup` libraries.

This project is designed to apply practical data science skills, including web scraping, data cleaning, exploratory data analysis, and visualization. The goal is to answer questions about trends, patterns, and shifts, in movie releases and revenues using scraped data structured into a pandas DataFrame.

The analysis explores questions such as:
- Which year had the highest total weekend box office revenue?
- Which movie had the highest-grossing opening weekend each year?
- How do weekend grosses change seasonally (e.g., summer vs. winter)?
- Which months have the highest concentration of movie releases?

Each of these questions was answered programmatically, and the graphs are visualized using the seaborn library.

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

## 📚 External Resources & References

### Data Visualization & Analysis

- **Seaborn Heatmap Documentation**  
  Waskom, M., et al. (n.d.). *seaborn.heatmap*. Seaborn. Retrieved April 20, 2025, from  
  [https://seaborn.pydata.org/generated/seaborn.heatmap.html](https://seaborn.pydata.org/generated/seaborn.heatmap.html)

- **Adding Data Labels to Bar Charts**  
  Stack Overflow. (2016). *Add data labels to seaborn factor plot*. Retrieved April 20, 2025, from  
  [https://stackoverflow.com/questions/39444665/add-data-labels-to-seaborn-factor-plot](https://stackoverflow.com/questions/39444665/add-data-labels-to-seaborn-factor-plot)

---

### Web Scraping

- **Bright Data - Web Scraping with Beautiful Soup**  
  Bright Data. (n.d.). *Beautiful Soup Web Scraping*. Retrieved April 20, 2025, from  
  [https://brightdata.com/blog/how-tos/beautiful-soup-web-scraping](https://brightdata.com/blog/how-tos/beautiful-soup-web-scraping)

- **GeeksforGeeks - Beautiful Soup Tutorial**  
  GeeksforGeeks. (n.d.). *Implementing web scraping in Python with BeautifulSoup*. Retrieved April 20, 2025, from  
  [https://www.geeksforgeeks.org/implementing-web-scraping-python-beautiful-soup/](https://www.geeksforgeeks.org/implementing-web-scraping-python-beautiful-soup/)

---

### Data Cleaning with Regular Expressions and Pandas

- **Python Regex HOWTO**  
  Python Software Foundation. (n.d.). *Regular Expression HOWTO*. Retrieved April 20, 2025, from  
  [https://docs.python.org/3/howto/regex.html](https://docs.python.org/3/howto/regex.html)

- **Stack Overflow - Pandas Apply Return Multiple Columns**  
  Stack Overflow. (2014). *Return multiple columns from pandas apply*. Retrieved April 20, 2025, from  
  [https://stackoverflow.com/questions/23586510/return-multiple-columns-from-pandas-apply](https://stackoverflow.com/questions/23586510/return-multiple-columns-from-pandas-apply)

- **Pandas Documentation - DataFrame.apply**  
  The pandas development team. (n.d.). *pandas.DataFrame.apply*. Retrieved April 20, 2025, from  
  [https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.apply.html?utm_source=chatgpt.com%5D%28https%3A%2F%2Fpandas.pydata.org%2Fdocs%2Freference%2Fapi%2Fpandas.DataFrame.apply.html%3Futm_)

