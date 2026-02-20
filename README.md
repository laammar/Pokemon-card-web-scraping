# Pokémon Cards Web Scraping & Profitability Analysis

## Project Overview
This project performs web scraping on a Pokémon card marketplace to extract pricing data for multiple card sets.  
It collects different price conditions (ungraded, Grade 9, PSA 10), calculates potential profit margins, applies filtering criteria, and exports structured results to Excel.

## Business Logic
The script identifies potentially profitable cards based on:

- Ungraded price < 50€
- Estimated profit > 100€

This allows quick detection of arbitrage opportunities between raw and graded cards.

## Technologies Used
- Python
- Requests
- BeautifulSoup
- Pandas

## Output
The filtered dataset is exported as an Excel file.  
An example output can be found in the `/outputs` folder.

## How to Run
Install dependencies:

pip install -r requirements.txt

Then execute the notebook inside the `/notebooks` folder.
