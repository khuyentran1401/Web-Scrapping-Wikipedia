# About this Project

Find the correlation between sunshine hours and depression rate in countries in the world

# Motivation

My roomate and I were discussing about the correlation between the sun and depression. To prove my point that less sun is correlated to depression rate, I gather the data to support my hypothesis. 

# Data

The data is retrieved from [Wikipedia](https://en.wikipedia.org/wiki/Epidemiology_of_depression)

# Tool

* [Beautful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): a Python library to pull data out of HTML and XML files. 

* Numpy, Pandas
* Matplotlib

# Medium Article and Notebook
* [Medium article](https://towardsdatascience.com/step-by-step-tutorial-web-scraping-wikipedia-with-beautifulsoup-48d7f2dfa52d?source=friends_link&sk=9d0e6525636b60b7457b658e64889a92): tutorial on how to scrape wikipedia and analyze the data
* [Notebook](https://github.com/khuyentran1401/Web-Scrapping-Wikipedia/blob/master/Web%20scrap%20wikipedia.ipynb)

# Result

. | Rank | DALY rate | Sunshine Hours/Year
------------ |------------ | ------------ | ------------ 
Rank | 1.000000	| -0.963597	| 0.346623
DALY rate	| -0.963597 |	1.000000 | -0.285906
Sunshine Hours/Year |	0.346623 | -0.285906	| 1.000000

# Discussion

The correlation is not as strong as I thought it would be. But we haven’t taken into account different factors such as the accurateness of the metric to determine to depression rate, the size the countries (the bigger the country, the more variation in sunshine hours/year), GDP, population, etc. More data should be gathered to attain a more accurate result.


