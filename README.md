# Books Web Scraper

## Project Overview
This project is a simple web scraping application built with Python. It extracts book titles and prices from the Books to Scrape website and stores the scraped data in a CSV file.

## Technologies Used
- Python
- Requests
- BeautifulSoup (bs4)
- Pandas

## Website
http://books.toscrape.com/

## Features
- Scrapes book titles
- Scrapes book prices
- Stores data in a CSV file
- Displays the first few records in the terminal

## Project Structure

```
books-web-scraper/
│
├── webscrapping.py
├── books_dataset.csv
└── README.md
```

## Installation

Install the required libraries:

```bash
pip install requests beautifulsoup4 pandas
```

## Run the Project

```bash
python webscrapping.py
```

## Output

The project generates:

- `books_dataset.csv` containing:
  - Book Name
  - Price

## Sample Output

| Book Name | Price |
|------------|--------|
| A Light in the Attic | £51.77 |
| Tipping the Velvet | £53.74 |

## Author

Priya Yadav
