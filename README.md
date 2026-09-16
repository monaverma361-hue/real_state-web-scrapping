# MagicBricks Property Scraper

## Project Overview

This project uses Selenium to scrape rental property listings from MagicBricks. The notebook searches for properties in Gurgaon, applies filters on the website, extracts selected property details, and saves the collected data in JSON format.

## Key Features

- Opens MagicBricks in a Chrome browser using Selenium.
- Handles the initial popup when it appears.
- Searches for Gurgaon property listings.
- Applies the Verified Properties filter.
- Selects a budget range using dropdown filters.
- Scrolls through the results page to load listings.
- Extracts property name, furnished/details field, tenant-preferred/details field, and rent.
- Saves the scraped data to .

## Technologies Used

- Python
- Jupyter Notebook
- Selenium
- NumPy
- JSON
- Chrome WebDriver

## Project Workflow

1. Import the required libraries for browser automation and data handling.
2. Define a helper function to close the MagicBricks popup if it appears.
3. Open MagicBricks in Chrome and search for Gurgaon properties.
4. Select a valid search suggestion and submit the search.
5. Open the Verified Properties results.
6. Apply minimum and maximum budget filters.
7. Scroll to the bottom of the results page so more listings load.
8. Scrape property details from each listing card.
9. Save the collected records into .

## Project Structure



## How to Run

1. Open the project folder.
2. Install the required packages:



3. Make sure Google Chrome is installed and Selenium can access a compatible Chrome WebDriver.
4. Open  in Jupyter Notebook or JupyterLab.
5. Run the notebook cells in order.
6. After the scraper finishes, check  for the collected data.

## Output/Results

The project creates a JSON file named . Each record contains selected listing details such as:

- 
- 
- 
- 

The current output file contains scraped MagicBricks property listing data.

## Requirements

The required Python packages are listed in :

- 
- 
- 

Install them using:


# real_state-web-scrapping
