# Web-Scrapping-Corona-Virus-data-into-Ms-Excel
Fetching the Corona Virus data across the world and scraping into Ms Excel.


Pre-requisites:
==========================
```
- python
- Beautiful soup
- pandas
- HTML
- CSS
```

What is Web Scrapping?:
==========================
Web scraping, also known as web data extraction, is the process of retrieving or “scraping” data from a website. This information is collected and then exported into a format that is more useful for the user. Be it a spreadsheet or an API. 

Steps:
==========================
1. Make Requests
2. Create Beautiful Soup object
3. Extract the data
4. Store the data
5. Create DataFrame
6. Export the data

The data source:
==========================
We need a webpage to fetch the coronavirus data from. So I am using the [Worldometer](https://www.worldometers.info/coronavirus/#countries) website here.

Required Libraries:
==========================
```
pip install requests
pip install lxml
pip install bs4
```

