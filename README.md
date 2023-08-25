# web-scraping-challenge
This challenge demonstrates the ability to extract information via both automated browsing using Splinter and HTML parsing with BeautifulSoup

## Part 1: Scrape Titles and Preview Tect from Mars News
In the notebook for part 1, I scraped the site and extracted the article title and the preview text.
Optional - we created a json file after import json - we looked at geekforgeeks.org for help with this conversion  mars_news.json

## Part 2: Scrape and Analyze Mars Weather Data
in the notebook for part 2, I scraped the site and extracted table data to a pandas DataFrame. 
I analyzed the data to answer some questions

1. Hou many months on Mars?
12 months

2. How Many Martian Days?
1867 days

3. What are the coldest and least coldest (warmest) months on Mars on average?
Coldest month on average is Month 3
The least coldest month on average is Month 8

4.  What are the months on Mars with the highest and lowest athmospheric pressure?
Highest Athmospheric pressure is Month 9
Lowest Athmospheric pressure is Month 6

5. How many days approximately in a Martian year
Peak to Peak estimate about 675 days
Trough to trough estimate about 660 days

Finally we data in the DataFrame was saved as a csv file mars_weather.csv

