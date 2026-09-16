# MagicBricks Property Scraper

## Project Overview

This project uses **Selenium and Python** to scrape rental property listings from MagicBricks. The scraper searches for properties in **Gurgaon**, applies selected filters, extracts property details from the listing cards, and saves the collected data in **JSON format**.

## Key Features

- Opens MagicBricks using Selenium and Chrome WebDriver.
- Handles the initial popup when it appears.
- Searches for rental properties in Gurgaon.
- Selects the required search suggestion.
- Applies the **Verified Properties** filter.
- Sets minimum and maximum budget filters.
- Scrolls through the results page to load property listings.
- Extracts selected property details.
- Saves the scraped data in JSON format.

## Technologies Used

- Python
- Jupyter Notebook
- Selenium
- NumPy
- JSON
- Chrome WebDriver

## Project Workflow

1. Import the required Python libraries.
2. Set up Chrome WebDriver using Selenium.
3. Open MagicBricks and handle the initial popup.
4. Search for rental properties in Gurgaon.
5. Select the appropriate search suggestion.
6. Apply the Verified Properties filter.
7. Set the minimum and maximum budget.
8. Scroll through the results to load available property listings.
9. Extract relevant details from each property card.
10. Store the scraped records in a list.
11. Save the collected data as a JSON file.

## Project Structure

```text
MagicBricks-Property-Scraper/
├── MagicBricks_Scraper.ipynb
├── output/
│   └── properties.json
├── requirements.txt
└── README.md
