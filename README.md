# Scraping Gold Price using Python
![](https://imgur.com/eZyTULA.png)
![](https://imgur.com/8xgzOus.png)

#### In this project I have created a web scraper that takes all the information about gold such as price over different `Carats`, Yesterday's Price for all the states present across India and compiles it into a CSV.
![](https://imgur.com/ySWxZoj.png?1)

---
Check out the Jupyter notebook here https://jovian.ai/abhishek-mehta2k/web-scraping-project 

---
### Project steps
Here is an outline of the steps we'll follow :

1. Download the webpage using `requests`
2. Parse the HTML source code using `BeautifulSoup` library and extract the desired information
3. Building the scraper components
4. Compile the extracted information into Python list and dictionaries
5. Converting the python dictionaries into `Pandas DataFrames`
5. Write information to the final CSV file
7. Future work and references

---
### Packages Used:
1. Requests — For downloading the HTML code from the IMDB URL
2. BeautifulSoup4 — For parsing and extracting data from the HTML string
3. Pandas — to gather my data into a dataframe for further processing

