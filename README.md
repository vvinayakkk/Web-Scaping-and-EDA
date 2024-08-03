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

![Screenshot 2024-08-03 134119](https://github.com/user-attachments/assets/fbb38171-fbbe-4dfa-95a8-dd8e1001526c)
![Screenshot 2024-08-03 134126](https://github.com/user-attachments/assets/6ea4153d-0e2c-432c-a6c8-78873485d430)
![Screenshot 2024-08-03 134140](https://github.com/user-attachments/assets/7eeedaf7-6c75-45d3-a080-06b3b64a1b92)

You can install these packages using pip:

```bash
pip install requests beautifulsoup4 pandas matplotlib

