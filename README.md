# LinkedIN_Scraper_Final

Overview:
The LinkedIn Company Scraper is a Python-based web scraping tool designed to automate the process of extracting company information from LinkedIn. It logs into LinkedIn using user credentials, navigates to the company search results, and extracts relevant data such as company names, industries, the number of employees, Website, Phone number and adress. The scraped data is stored in a CSV file for further analysis or usage.

Features
-Automated Login: The scraper uses Selenium to log into LinkedIn with provided user credentials.
-Data Extraction: Extracts key information about companies including company name, industry, and the number of employees.
-Location Filter: Filters companies based on their location, specifically targeting companies in Hyderabad.
-Pagination Handling: Automatically navigates through the first three pages of search results to gather data.
-Duplicate Handling: Ensures no duplicate entries in the CSV file by updating existing entries with the latest information.
-Error Handling: Includes robust error handling to manage common web scraping issues such as timeouts and missing elements.
