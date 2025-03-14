# PlayStation-Web-Scrapping

# Amazon Web Scraping

## Overview
This project focuses on web scraping Amazon to extract product details such as title, price, rating, reviews, and availability. The data is then stored in a Pandas DataFrame and saved as a CSV file for further analysis.

## Features
- Extracts product title, price, rating, number of reviews, and availability status.
- Uses BeautifulSoup and requests to parse Amazon product pages.
- Saves the extracted data into a CSV file for easy access.
- Handles missing data to ensure data quality.

## Prerequisites
Ensure you have the following Python libraries installed: BeautifulSoup4, Requests, Pandas, and NumPy.

## Usage
1. **Import Required Libraries**: The script imports necessary libraries for web scraping, data processing, and storage.

2. **Define Functions to Extract Product Details**: Functions are created to extract key product attributes like title, price, rating, reviews, and availability from Amazon product pages.

3. **Set Headers and Define URL**: The script sets HTTP headers, including a user agent, to prevent being blocked by Amazon. It then defines a search URL for PlayStation 4.

4. **Send HTTP Request and Parse Webpage**: The script sends a request to Amazon, retrieves the HTML content, and parses it using BeautifulSoup.

5. **Extract Product Links**: It extracts product links from the search results to access individual product pages.

6. **Scrape Individual Product Pages**: For each product link, the script extracts the product details by visiting the respective page and retrieving relevant information.

7. **Store Data in a DataFrame and Save to CSV**: The extracted data is stored in a Pandas DataFrame, cleaned to remove incomplete entries, and then saved as a CSV file for further analysis.

## Output
The script generates a CSV file `amazon_data.csv` containing extracted product details.


