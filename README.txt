📈 NIFTY 50 Web Scraping Project
📌 Project Overview

This project focuses on web scraping real-world financial data from Wikipedia using Python.
The goal is to extract NIFTY 50 constituent companies data, convert it into a structured format, and prepare it for further analysis and visualization.

This project is part of my Data Analyst portfolio and demonstrates practical skills in:

Web scraping

Handling HTTP requests

HTML parsing

Data extraction using Python libraries

🌐 Data Source

Website: Wikipedia

Page: NIFTY 50

URL: https://en.wikipedia.org/wiki/NIFTY_50

Wikipedia was chosen because it provides a structured and realistic data table similar to sources analysts often work with in real-world scenarios.

🛠️ Tools & Libraries Used

Python

Requests – to fetch webpage content

BeautifulSoup (bs4) – to parse HTML and extract table data

Jupyter Notebook – for development and documentation

📂 Project Structure
Nifty50-WebScraping/
│
├── Nifty50_WebScraping_Project.ipynb   # Main notebook
├── README.md                           # Project documentation

🔍 What This Project Does

Sends an HTTP request with custom headers to avoid request blocking (403 errors)

Parses HTML content using BeautifulSoup

Identifies and extracts the NIFTY 50 table from the webpage

Collects company-level data into a structured format ready for analysis

🧹 Data Cleaning Status

✔ Data successfully scraped from the source

⏳ Data cleaning and preprocessing will be handled in a separate dedicated project to maintain clarity and modularity

🚀 Future Enhancements

Convert scraped data into a Pandas DataFrame

Perform data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Data visualization using Plotly / Matplotlib

Automate periodic data updates

🎯 Learning Outcomes

Understanding how websites handle HTTP requests

Using headers and user-agents to bypass access restrictions

Navigating and extracting HTML tables

Building a portfolio-ready web scraping project

👤 Author

Naveen Kumar
Aspiring Data Analyst

🔗 GitHub: https://github.com/NaveenKumar1822

🔗 LinkedIn: https://www.linkedin.com/in/naveen840/

📧 Email: sknaveen148@gmail.com

⭐ Acknowledgements

Wikipedia for providing open-access financial data

Python open-source community