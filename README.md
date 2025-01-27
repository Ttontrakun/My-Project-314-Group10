# My-Project-314-Group10
Essential details about the Sanitary Napkin Project, featuring example code and fundamental usage instructions.

## Project Overview

This project focuses on analyzing sales data for sanitary napkins. It involves collecting data from various sources and performing analysis to gain insights into the sales of sanitary napkins in different regions. The data is used to create charts and perform various analyses to provide a comprehensive view of the sanitary napkin market.

## Files in This Project

### README.md
This file provides an overview of the project. It includes essential details about the Sanitary Napkin Project, featuring example code and fundamental usage instructions. It explains that the project focuses on analyzing sales data for sanitary napkins, collecting data from various sources, and performing analysis to gain insights into the sales of sanitary napkins in different regions.

### scraping data 
This Jupyter Notebook contains code for scraping product data from Lazada's website. Here's a breakdown of what the code does:

1. **Import Libraries**: The code imports necessary libraries such as `selenium` for web scraping, `BeautifulSoup` for parsing HTML, `time` for handling delays, and `pandas` for data manipulation.

2. **Class Definition**: A class named `ScrapeLazada` is defined to encapsulate the scraping functionality.

3. **Scrape Method**: The `scrape` method is defined within the `ScrapeLazada` class. This method takes an optional parameter `num_pages` which specifies the number of pages to scrape (default is 34).

4. **Base URL**: The base URL for the Lazada search results page is defined.

5. **WebDriver Initialization**: A Chrome WebDriver instance is created to interact with the web browser.

6. **Product List**: An empty list named `products` is initialized to store the scraped product data.

7. **Page Loop**: A loop iterates over the specified number of pages. For each page, the URL is formatted with the current page number, and the WebDriver navigates to that URL.

The code snippet provided is just the beginning of the scraping process. The rest of the code would typically include extracting product details from the page, handling pagination, and saving the scraped data to a file or database.

### clean data.xlsx
This file contains the cleaned and processed data collected from various sources. It is used for analysis and visualization purposes. The data in this file is structured and ready for further analysis.

### analysis.ipynb
This Jupyter Notebook contains code for analyzing the cleaned data. It includes various data analysis techniques and visualizations to gain insights into the sales of sanitary napkins. The notebook uses libraries such as `pandas` for data manipulation and `matplotlib` for creating charts and graphs.


