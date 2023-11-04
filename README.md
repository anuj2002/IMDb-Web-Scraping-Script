## IMDb Web Scraping Script

**Description:** This Python script is designed to scrape movie information from IMDb using the Selenium library. It allows you to perform an advanced search on IMDb and scrape details of movies matching your criteria.

**Prerequisites:**

* Python 3.10
* Selenium
* Chrome WebDriver

**Installation:**

```bash
pip install selenium
```
## Usage

To use the script:

1. Download the Chrome WebDriver and provide its path in the script.
2. Clone or download the script to your local machine.
3. Run the script using the following command:

```bash
python imdb_scraping_script.py
```

The script will open a Chrome browser, navigate to IMDb, perform an advanced search, and scrape movie details.

**Advanced Search Parameters:**

You can customize the following advanced search parameters:

* **Title Type:** Choose "Feature Film," "TV Movie," or both.
* **Release Date:** Define a range of release dates.
* **User Rating:** Set a minimum and maximum user rating.
* **Oscar Nominated:** Check this option if you want to include Oscar-nominated movies.
* **Color:** Check this option if you want to include colored movies.
* **Language:** Choose the language of the movies.
* **Sort Order:** Select how you want to sort the results.
* **Results per Page:** Choose the number of movies to display on each page.

**Scraped Data:**

The script scrapes the following data for each movie:

* Movie Name
* Releasing Year
* Metascore
* Director(s)
* Earnings

**Output:**

The scraped data is stored in a CSV file named "movie.csv" in the same directory as the script.

**Limitations:**

This script is designed for educational and research purposes and may be subject to IMDb's terms of service.

**Acknowledgments:**

* Selenium
* Pandas

Feel free to modify and enhance the script to meet your specific needs. Happy web scraping!
