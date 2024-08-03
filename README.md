# Web-Scaping-and-EDA
# Car Data Web Scraping Project

## Overview

This project focuses on scraping car data from Cars24 for various city-specific pages and performing data analysis. The scraping is done using BeautifulSoup and requests, while the analysis involves plotting key metrics to understand the data better.

## Prerequisites

Ensure you have Python installed along with the following packages:

- `requests`: For sending HTTP requests.
- `beautifulsoup4`: For parsing HTML.
- `pandas`: For handling data.
- `matplotlib`: For plotting data.

## Web Scraping

### Description

The `scrape_cars.py` script is responsible for:

1. **Sending an HTTP Request**: Sends a request to the target city-specific page on Cars24 to retrieve the HTML content of the page.
2. **Parsing HTML Content**: Uses BeautifulSoup to parse the HTML and extract relevant details about cars, such as:
   - **Title**: The name or model of the car.
   - **Price**: The listed price of the car.
   - **Year**: The manufacturing year of the car.
3. **Storing Data**: Saves the extracted car details into a CSV file, which can be used for further analysis and visualization.

You can install these packages using pip:

```bash
pip install requests beautifulsoup4 pandas matplotlib

