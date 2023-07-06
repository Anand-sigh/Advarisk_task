# Advarisk_task

## Scraping data from Companies incorporated in India website and storing the data in MongoDB
. This Adavarisk.ipynb script demonstrates how to scrape a website and store the scraped data into a MongoDB database using Python.

##Prerequisites
. make sure you have the following installed on your machine 
. Python 
. requests 
. scrapy 
. hashlib 
. json 
. mondodb and pymongo

# Import necessary libraries in the beginning
. import requests 
. import scrapy . 
. from scrapy.http import HtmlResponse 
. import hashlib 
. import json 
. from pymongo import MongoClient

# Scrape the website using python and imported libraries
. As all the data on the page page are available inside table rows which are inside table tag with id table
. We will iterate through all the rows of the table and get data from td tags 
. If data cleaning is required we will do that as well

# Push all data in mongodb database
. Install pymongo 
. pymongo is the official MongoDB driver for Python
. Make connection with database and create a new database
. inside newdatabse create a collection and put all data inside collection

#Final run script 
#Run the script
