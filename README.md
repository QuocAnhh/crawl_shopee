# Crawl Shopee

A Python-based web scraper for extracting data from Shopee e-commerce platform.

## Overview

This project is designed to crawl and extract data from the Shopee marketplace. The tool helps collect product information, prices, reviews, and other relevant data from Shopee's website.

## Features

- Extract product information from Shopee
- Handle pagination for comprehensive data collection
- Manage request headers and cookies to mimic browser behavior
- Process and structure the extracted data
- Export data to usable formats

## Requirements

- Python 3.10+
- Required Python packages (install via `pip install -r requirements.txt`):
  - pandas
  - selenium
  - Genlogin

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/QuocAnhh/crawl_shopee.git
   cd crawl_shopee
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Configure the crawler parameters in the configuration file or directly in the script
2. Run the main script:
   ```bash
   python crawl.py
   ```

3. The extracted data will be saved in the specified output format (e.g., CSV, JSON)

## Configuration

Adjust the crawler settings as needed:
- Target URLs
- Search queries
- Number of pages to crawl
- Output file format and location
- Request delays to avoid being blocked

## Notes

- This tool is for educational purposes only
- Always respect Shopee's terms of service and robots.txt directives
- Implement appropriate delays between requests to avoid IP blocks

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Contact

Github - [GitHub](https://github.com/QuocAnhh)

Facebook - https://www.facebook.com/quocanh161004

Telegram - @quoccankk
