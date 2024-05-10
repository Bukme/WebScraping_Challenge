# WebScraping_Challenge

# Mars Data Scraping and Analysis

This project involves scraping data from various Mars-related websites and analyzing it using Python. There are two main parts to this project:

## Part 1: Scraping Mars News Articles

In this part, I scrape news articles from a Mars news website. The tasks involved are as follows:

### Step 1: Visit the Website

Using automated browsing, I visit the Mars news site to identify which elements to scrape. This step includes inspecting the page using Chrome DevTools.

### Step 2: Scrape the Website

I create a Beautiful Soup object to extract text elements from the website.

### Step 3: Store the Results

The titles and preview text of the news articles scraped are stored in Python dictionaries and then in a list. Finally, the list is printed to display the results.

## Part 2: Scraping and Analyzing Mars Weather Data

This part focuses on scraping and analyzing Mars weather data from another website. The steps involved are as follows:

### Step 1: Visit the Website

I use automated browsing to visit the Mars Temperature Data Site and inspect the page to identify which elements to scrape.

### Step 2: Scrape the Table

A Beautiful Soup object is created to scrape the data in the HTML table.

### Step 3: Store the Data

The scraped data is assembled into a Pandas DataFrame. I also examine and change data types if necessary.

### Step 4: Analyze the Data

The dataset is analyzed to answer several questions:
1. How many months exist on Mars?
2. How many Martian (and not Earth) days' worth of data exist?
3. What are the coldest and the warmest months on Mars?
4. Which months have the lowest and highest atmospheric pressure on Mars?
5. About how many terrestrial (Earth) days exist in a Martian year?

Plots are generated to visualize the data and answer these questions.

## Conclusion

This project demonstrates how to scrape data from websites using Python's Beautiful Soup and Splinter libraries and analyze it using Pandas. It provides valuable insights into Mars news and weather patterns.

## References

Beautiful Soup documentation¶. Beautiful Soup Documentation - Beautiful Soup 4.12.0 documentation. (n.d.). https://www.crummy.com/software/BeautifulSoup/bs4/doc/ 

HTML. HTML Standard. (n.d.). https://html.spec.whatwg.org/ 

Splinter¶. splinter. (n.d.). https://splinter.readthedocs.io/en/latest/ 

YouTube. (2023, July 11). Scraping data from a real website | web scraping in Python. YouTube. https://www.youtube.com/watch?v=8dTpNajxaH0 

Other resourceful insight gotten from class, other students and tutor. 
