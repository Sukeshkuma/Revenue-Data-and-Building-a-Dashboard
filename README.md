# Revenue-Data-and-Building-a-Dashboard
This project focuses on extracting and visualizing stock and revenue data for two companies: Tesla and GameStop. The data is collected using both API-based extraction and web scraping techniques.

We used Jupyter Notebook along with several Python libraries such as:
Tools & Technologies Used

* Python
* Jupyter Notebook
* pandas
* yfinance
* matplotlib
* BeautifulSoup (bs4)
* nbformat

Project Objectives:

* Extract stock data using the yfinance API
* Extract revenue data using web scraping
* Clean and process the collected data
* Visualize stock price and revenue trends
* Build a dashboard-style visualization

Project Contents

1. Extracting and Visualizing Stock Data
2. Table of Contents

* 2.1 Define a function to create graphs
* 2.2 Use yfinance to extract Tesla stock data
* 2.3 Use web scraping to extract Tesla revenue data
* 2.4 Use yfinance to extract GameStop stock data
* 2.5 Use web scraping to extract GameStop revenue data
* 2.6 Plot Tesla stock graph
* 2.7 Plot GameStop stock graph

3. Graphing Function

In this section, we define a function called **make_graph**.

This function takes the following inputs:

* A dataframe containing stock data (**must include "Date" and "Close" columns**)
* A dataframe containing revenue data (**must include "Date" and "Revenue" columns**)
* The name of the stock

The function generates a visualization comparing stock prices and revenue over time.

4. Business Requirement Analysis

In this section, we answer key business-related questions based on the extracted data. These insights help in understanding the financial trends and performance of the companies.

Conclusion

This project demonstrates how to combine API data extraction and web scraping techniques to analyze real-world financial data. It also highlights the importance of data cleaning and visualization in deriving meaningful business insights.

Skills: Python, Jupyter Notebook, Panda, Matplotlib, Web Scarping.
