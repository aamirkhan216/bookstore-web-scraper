# Bookstore Intelligence: Web Scraper

A web scraper that turns the book listings on https://books.toscrape.com/ into a clean dataset for business analysis.

## What it does
- Downloads catalogue pages with `requests`
- Parses each book card with `BeautifulSoup`
- Extracts title, price, rating and availability, plus the product URL
- Converts star ratings from words (One to Five) into numbers 1 to 5
- Loops through 5 pages (100 books) using one reusable function
- Saves the result as `competitor_books.csv`
- Answers seven business questions and solves a £100 purchasing challenge

## Files
- `Bookstore_Intelligence_Assignment_Final.ipynb`: the scraper and analysis
- `competitor_books.csv`: the dataset produced by the scraper

## Tools
Python, requests, BeautifulSoup, pandas, matplotlib

## Note
Built for educational purposes on a sandbox website designed for scraping practice.
