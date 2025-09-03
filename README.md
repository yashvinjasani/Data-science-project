Stock Data Extraction and Visualization

Project Overview

This project demonstrates a complete workflow for gathering and analyzing financial data. It extracts historical stock prices for Tesla (TSLA) and GameStop (GME) using the yfinance library and scrapes their revenue data from web pages using BeautifulSoup. Finally, it uses plotly to create interactive visualizations that plot the historical share price against the company's revenue.

This project is a practical application of key data science skills, including web scraping, API usage, data manipulation with pandas, and data visualization.

Features:

1. Stock Data Retrieval: Fetches historical market data for specified stock tickers.
2. Web Scraping: Parses HTML to extract tabular revenue data.
3. Data Cleaning: Processes and cleans the extracted data to ensure it's in a usable format for analysis.
4. Data Visualization: Generates plots to compare stock performance with financial revenue over time.

Tech Stack:
1. Python 3
2. Jupyter Notebook
3. Libraries:
               yfinance: For fetching stock market data.
               pandas: For data manipulation and analysis.
               requests: For making HTTP requests to web pages.
               beautifulsoup4: For parsing HTML and XML documents.
               plotly: For creating interactive graphs and visualizations.
   
Installation

To get this project running on your local machine, follow these steps:

STEP 1
Clone the repository:
git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
cd your-repository-name

STEP 2
Install the required Python libraries:
pip install yfinance pandas requests beautifulsoup4 plotly

STEP 3
How to Run
Once the installation is complete, you can run the project using Jupyter Notebook:
jupyter notebook "final python project (1).ipynb"

Execute the cells in the notebook sequentially to see the process of data extraction, processing, and the final visualizations.


Visualizations:

The script will generate two plots as output:
1. Tesla Historical Share Price vs. Revenue
2. GameStop Historical Share Price vs. Revenue
These plots provide a clear visual comparison between the market valuation (stock price) and the actual financial performance (revenue) of the companies.

Author
Yashvin Jasani
LinkedIn: www.linkedin.com/in/yashvin-jasani-61190a2a4
