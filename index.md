# Exploratory Data Analysis in Python

When you first encounter a dataset that may be of use in your research, you will need a strategy to determine the content and quality of that dataset to see if can be of use to you.  Not all data (far too little) comes with comprehensive documentation and metadata, or documentation that is kept up to date.  This tutorial will walk you through the process of exploring a dataset using python and the pandas library.  

### Digital Workshop Series
You can find the complete list of Digital Scholarhsip Workshops here: You can find a directory of the currently available tutorials here:  [https://librarybeales.github.io/dsworkshops/](https://librarybeales.github.io/dsworkshops/)

### Constellate or Binder?

Constellate is available to Case Western students, staff, and faculty.  To use Constellate you will have to create a JSTOR login that is separate from your University login.  Instructions for that are here:  <a href="https://librarybeales.github.io/CreateLogin/" target=blank>Making a Constellate Account</a>.

If you are not part of Case you can launch these tutorials using the Launch Binder button.  ![A binder launch button](https://mybinder.org/static/images/badge_logo.svg)  Any changes you make or work you complete will be deleted when closing the tab or window.  You can, however, download a copy of file you've been working in before closing the browser.  
## So, where do I find data?

Data is available from many sources across a wide variety of disciplines, and with a wide range of quality and usefulness. Getting into the question of, "Where to find data?", here would derail the entire python tutorial, but it is an important one to address.  Finding data is a skill that you will develop as you gain expertise in your subject area.  Learning the exploratory data analysis process is a part of that.  

Librarians are always available to help you locate resources, including datasets that will enrich your work.  Email [freedmancenter@case.edu](mailto:freedmancenter@case.edu) to get in touch with the Digital Scholarship Team at the Kelvin Smith Library.  We can help you locate essential daat to support your research, or connect you with someone who can.

Case Western is also building a research data index here: <a href ="link!">COMING SOON!</a> 


## Project #1: Importing Data and Discovering Basic Information

This first lesson will use basic python and the `pandas` package to introduce the data import process and the early exploration process.  All the lessons on this page use this [2014 Census Data](https://raw.githubusercontent.com/LibraryBeales/Exploratory_Data_Analysis/refs/heads/main/adult.csv) dataset.  

In this project you will:
1. Learn how to import the necessary python libraries.
2. Use the `read_csv` function in pandas to import a csv file.
3. Discover the size of the dataset.
4. Discover the types of data in the dataset. 
5. Learn how to modify data types to improve performance, accuracy and scalability.

<a href="https://constellate.org/lab?repo=https%3A%2F%2Fgithub.com%2FLibraryBeales%2FWeb-Scraping&filepath=eda1.ipynb" target="_blank">![A constellate launch button](https://constellate.org/images/constellate-badge.svg)</a>   <a href="https://mybinder.org/v2/gh/LibraryBeales/Web-Scraping/main?labpath=eda1.ipynb" target="_blank">![A binder launch button](https://mybinder.org/static/images/badge_logo.svg)</a>


## Project #2: Data Visualization for Univariate and Bivariate Analysis

In this lesson, you will learn how to identify missing data, outliers, and 

In this project you will:
1. Use the `Inspect` tool in your web browser to explore the structure of the <a href="https://books.toscrape.com/">Books to Scrape</a> website.
2. Understand how book titles on the site are tagged/classified. 
3. Understand and use a python script to crawl the web page and extract only the data that meets the classification criteria we identified for titles in step 2.
4. Look at the list of titles we scraped.  Identify problems with the data and explore an alternative strategy of using Beautiful Soup to get the correct titles.
5. Write the list of correct titles to a file. 

<a href="https://constellate.org/lab?repo=https%3A%2F%2Fgithub.com%2FLibraryBeales%2FWeb-Scraping&filepath=scrape2.ipynb" target="_blank">![A constellate launch button](https://constellate.org/images/constellate-badge.svg)</a>  <a href="https://mybinder.org/v2/gh/LibraryBeales/Web-Scraping/main?labpath=scrape2.ipynb" target="_blank">![A binder launch button](https://mybinder.org/static/images/badge_logo.svg)</a>


## Project #3: Identify missing data and decide how to handle them.

Build a scraper that collects multiple data points about each book based upon specific criteria.

In this project you will:
1. Determine what data we are able to collect about each book listed in the store.  
2. Use the `Inspect` tool in your web browser to identify the web page structure for those pieces of data. 
3. Understand and use a python script to crawl the web page and extract only the data that meets the classification criteria we identified in steps 1 and 2.
4. Write the data to a csv file. 

<a href="https://constellate.org/lab?repo=https%3A%2F%2Fgithub.com%2FLibraryBeales%2FWeb-Scraping&filepath=scrape3.ipynb" target="_blank">![A constellate launch button](https://constellate.org/images/constellate-badge.svg)</a>  <a href="https://mybinder.org/v2/gh/LibraryBeales/Web-Scraping/main?labpath=scrape3.ipynb" target="_blank">![A binder launch button](https://mybinder.org/static/images/badge_logo.svg)</a>

## Project #4: Identify outliers and decide how to handle them.

In this project you will:
1. Use the `Inspect` tool to explore how <a href="https://books.toscrape.com/">Books to Scrape</a> handles navigation between pages.
2. Understand and use a python script to direct the web scraper to a navigate to the next page if there is one, and scrape the specified data from there, and repeat this process until there are no more pages.
3. Examine the data to see if our scraper worked the way we think it should.
4. Write the data to a csv file. 

<a href="https://constellate.org/lab?repo=https%3A%2F%2Fgithub.com%2FLibraryBeales%2FWeb-Scraping&filepath=scrape4.ipynb" target="_blank">![A constellate launch button](https://constellate.org/images/constellate-badge.svg)</a>  <a href="https://mybinder.org/v2/gh/LibraryBeales/Web-Scraping/main?labpath=scrape4.ipynb" target="_blank">![A binder launch button](https://mybinder.org/static/images/badge_logo.svg)</a>

## Bonus Project: Data Visualization with Plotly.

In this project you will:
1. Examine the csv file we saved from the previous project and determine what values we would like to visualize.  
2. Look at the <a href="https://plotly.com/python/">Plotly</a> package for Python and determine which kinds of graphs we will could create with the data.  
3. Understand and use a python script to generate those graphs using the data we scraped from the <a href="https://books.toscrape.com/">Books to Scrape</a> website.
4. Save those graphs to a file.

[![Launch in Constellate badge](https://constellate.org/images/constellate-badge.svg)](https://constellate.org/lab?repo=https%3A%2F%2Fgithub.com%2FLibraryBeales%2FWeb-Scraping)  <a href="https://mybinder.org/v2/gh/LibraryBeales/Web-Scraping/main?labpath=scrape5.ipynb" target="_blank">![A binder launch button](https://mybinder.org/static/images/badge_logo.svg)</a>
