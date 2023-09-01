# web_scraping_challenge
web scraping assignment for UCF bootcamp

## Part 1: Scrape Titles and Preview Text from Mars News

### 1. Use automated browsing to visit the Mars news site Links to an external site.. Inspect the page to identify which elements to scrape.
	
### 2. Create a Beautiful Soup object and use it to extract text elements from the website.
	
### 3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
	
### 4. Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:
		
	- Store all the dictionaries in a Python list.
		
	- Print the list in your notebook.
### 5. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)
	
## Part 2: Scrape and Analyze Mars Weather Data

### 1. Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
	
### 2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
	
### 3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
	
	- id: the identification number of a single transmission from the Curiosity rover
		
	- terrestrial_date: the date on Earth
		
	- sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
		
	- ls: the solar longitude
		
	- month: the Martian month
		
	- min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
		
	- pressure: The atmospheric pressure at Curiosity's location
		
### 4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
	
### 5. Analyze your dataset by using Pandas functions to answer the following questions:

	- How many months exist on Mars?
	
	- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
	
	- What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question: 
	
		- Find the average minimum daily temperature for all of the months.
		
		- Plot the results as a bar chart.
	
	- Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
	
		- Find the average daily atmospheric pressure of all the months.
		
		- Plot the results as a bar chart.
		
	- About how many terrestrial (Earth) days exist in a Martian year? To answer this question: 
	
		- Consider how many days elapse on Earth in the time that Mars circles the Sun once.
		
		- Visually estimate the result by plotting the daily minimum temperature.
		
### 6. Export the DataFrame to a CSV file.


## Resources:

https://stackoverflow.com/questions/2136267/beautiful-soup-and-extracting-a-div-and-its-contents-by-id

https://stackoverflow.com/questions/69951839/scrape-data-to-store-into-pandas-dataframe

https://stackoverflow.com/questions/20889790/get-text-of-children-in-a-div-with-beautifulsoup

https://stackoverflow.com/questions/43291165/how-to-append-multi-dimensional-array-using-for-loop-in-python

https://stackoverflow.com/questions/63084421/scrape-web-table-to-multi-dimensional-array-list

https://stackoverflow.com/questions/64457334/python-beautifulsoup-how-to-get-text-from-tdtext-td

https://stackoverflow.com/questions/15891038/change-column-type-in-pandas

https://www.geeksforgeeks.org/change-data-type-for-one-or-more-columns-in-pandas-dataframe/#

https://www.geeksforgeeks.org/how-to-count-occurrences-of-specific-value-in-pandas-column/

https://stackoverflow.com/questions/43855474/changing-sort-in-value-counts

https://stackoverflow.com/questions/17679089/pandas-dataframe-groupby-two-columns-and-get-counts

https://sparkbyexamples.com/pandas/pandas-convert-groupby-output-from-series-to-dataframe/

https://stackoverflow.com/questions/28506907/how-to-make-matplotlib-show-all-x-coordinates

https://sparkbyexamples.com/pandas/pandas-groupby-sort-within-groups/

https://stackoverflow.com/questions/72040442/change-order-of-numbers-in-x-tick-labels-matplotlib

https://stackoverflow.com/questions/44068548/how-to-change-type-of-values-in-list-from-strings-to-integers

https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html

