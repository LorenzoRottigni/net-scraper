# WAN-scraper

## Overview
This is a web scraping project using Python Scrapy to collect data from a list of random websites. The goal is to gather information on website structure, content, and other relevant data for analysis.

## Requirements
- Python 3.x
- Scrapy

## Installation & Usage
1. Clone the repository: `git clone https://github.com/LorenzoRottigni/WAN-scraper.git`
2. Create venv "scraper": `python3 -m venv scraper`
3. Activate scraper venv: `source scraper/bin/activate`
4. Install dependencies: `pip3 install -r requirements.txt`
5. Run Scrapy spider: `scrapy crawl wan_scraper`
6. The spider will visit the URLs in the `start_urls` list in `wan_scraper/spiders/wan_scraper.py`, collect data, and save it to a CSV file located in the project directory.

## Additional Information
- The spider is set to obey the `robots.txt` file on each website visited, but please use caution and follow ethical scraping practices.
- Feel free to modify the spider's behavior to suit your needs by editing the code in `wan_scraper/spiders/wan_scraper.py`.
- For more information on using Scrapy, please refer to the [official documentation](https://docs.scrapy.org/en/latest/index.html).
