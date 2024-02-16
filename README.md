# Mars-News-and-Mars-Weather
Challenge#11 HW

Background \
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage. \

In this assignment, you will submit the following deliverables: \
Deliverable 1: Scrape titles and preview text from Mars news articles. \
Deliverable 2: Scrape and analyze Mars weather data, which exists in a table. \

Part 1: Scrape Titles and Preview Text from Mars News \
Open the Jupyter Notebook in the starter code folder named "part_1_mars_news.ipynb". You will work in this code as you follow the steps below to scrape the Mars News website. \
1. Use automated browsing to visit the Mars news site provided within. Inspect the page to identify which elements to scrape by using Chrome DevTools. \
2. Create a Beautiful Soup object and use it to extract text elements from the website. \
3. Extract the titles and preview text of the news articles that you scraped. Store as follows: \
Store each title-and-preview pair in a Python dictionary and give each dictionary two keys: title and preview. Store all the dictionaries in a Python list. Print the list in your notebook.\

Part 2: Scrape and Analyze Mars Weather Data \
Open the Jupyter Notebook in the starter code folder named "part_2_mars_weather.ipynb". You will work in this code as you follow the steps below to scrape and analyze Mars weather data. \
1. Use automated browsing to visit the Mars Temperature Data Site provided within. Inspect the page to identify which elements to scrape by using Chrome DevTools. \
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. \
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. \
4. Examine the data types that are currently associated with each column. If necessary, convert to the appropriate datetime, int, or float data types. Use the Pandas astype and to_datetime methods to accomplish this task. \
5. Analyze your dataset by using Pandas functions to answer the following questions: \
a) How many months exist on Mars? \
b) How many Martian (and not Earth) days worth of data exist in the scraped dataset? \
c) What are the coldest and warmest months on Mars? Find the average minimum daily temp for all months and Plot the results as a bar chart. \
d) Which months have the lowest and highest atmospheric pressure on Mars? Find the average daily atmospheric pressure of all months and Plot the results as a bar chart. \
e) About how many terrestrial (Earth) days exist in a Martian year? Visually estimate the result by plotting the daily minimum temperature. \
6. Export the DataFrame to a CSV file. \

This was a very interesting assignment! I was able to learn how to do web scraping on websites, extract relevant data, sort, and analyze data and draw meaningful conclusions from visuals. Overall, this task was completed using classroom exercises, Tutoring, Stack Overflow, and Google. 
