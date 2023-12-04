# Mars Challenge Project

## Part 1: Scrape Titles and Preview Text from Mars News

In this part of the project, we utilized automated browsing with Splinter to visit the Mars news site. The HTML code was then extracted using Beautiful Soup.

### Extraction of Titles and Preview Text

The titles and preview text of the Mars news articles were scraped and extracted from the HTML. We stored this information in a list of dictionaries (Python data structure)

## Part 2: Scrape and Analyze Mars Weather Data

### Data Extraction and Analysis

For the Mars weather data, we used Splinter and Beautiful Soup for data extraction. This ensured that the columns had the correct headings and data types in the resulting DataFrame.

### Data Analysis Questions

We answered the following questions by analyzing the weather data:

- How many months exist on Mars?
- How many Martian days' worth of data are available?

### Data Visualization

To support our answers, we created visualizations for the following questions:

- Which month, on average, has the lowest and highest temperature?
- Which month, on average, has the lowest and highest atmospheric pressure?
- An estimate of the number of terrestrial days in a Martian year was visually represented

### Exporting Data

Finally, we exported the DataFrame into a CSV file 

### Files

- [mars_df.csv](mars_df.csv): The exported DataFrame.
- [part_1_mars_news.ipynb](part_1_mars_news.ipynb): Jupyter Notebook for Part 1.
- [part_2_mars_weather.ipynb](part_2_mars_weather.ipynb): Jupyter Notebook for Part 2.