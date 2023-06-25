# Amazon-Web-Scraper-Project
# Web Scraping Amazon Mobiles

This repository contains a Python script that demonstrates web scraping of mobile phone data from the Amazon website. The script uses the `requests` library to send HTTP requests and the `BeautifulSoup` library to parse the HTML content.

## Requirements

To run the script, you'll need the following:

- Python 3.x
- `requests` library
- `BeautifulSoup` library
- `pandas` library

You can install the required libraries using the following command:


## Usage

1. Clone the repository to your local machine.
2. Open the script file `scrape_mobiles.py` and ensure that the required libraries are installed.
3. Run the script using Python: `python scrape_mobiles.py`.
4. The script will scrape mobile phone data from the Amazon website and display the results in the console.

## Explanation of HTML Tags

The script uses various HTML tags and classes to extract the desired information from the Amazon website. Here's an explanation of the HTML tags used:

- `<div data-component-type="s-search-result">`: This tag represents each individual mobile phone item on the search results page.

- `<span class="a-size-medium a-color-base a-text-normal">`: This tag contains the product title of the mobile phone.

- `<span class="a-icon-alt">`: This tag contains the rating of the mobile phone.

- `<span class="a-price-whole">`: This tag contains the price of the mobile phone.

The script finds these HTML elements using the `find` and `find_all` methods provided by BeautifulSoup, and extracts the desired information from the text content of these elements.
