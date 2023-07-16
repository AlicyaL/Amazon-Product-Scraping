# Scraping Amazon Products based on a User Search
===========================================================================

An automated scraping tool that locates a particular product and, by utilizing the Selenium Webdriver, crawls and extracts all the information based on a user search. This is an updated version of the project with the new Selenium update as well as improvements in file organization, code refactoring, and improvements.

</br>

<div align="center">
    <img width="75%" src="img/amazon1.gif" alt="amazon.gif" >
</div>

</br></br>

### Introduction
Browsing Amazon can be very confusing due to inconsistent layouts and web page structure. 
More importantly, the site can often be quite slow to browse due to so much traffic. 
Furthermore, comparing multiple products is much more difficult to infer as it requires browsing 
all the links for different products. 

The primary incentive of this project is to bypass the inconvenience a user would face by 
automating the search procedure on the Amazon site, scraping relevant information, and 
displaying comprehensively in a tabular format making it easy for the user to compare 
and analyze for a better purchase decision on Amazon.

</br></br>

![alt text](https://github.com/shahriar-rahman/Amazon-Product-Scraping/blob/main/img/amazon_products.JPG)

</br></br>

## Project Organization
---------------------------------------------------------

    ├── LICENSE
    ├── Makefile             <- Makefile with various commands
    ├── README.md        <- The top-level README for developers using this project.
    ├── scraping_data
    │   ├── csv              <- Data in csv format compatible with pandas dataframe.
    │   ├── excel           <- Data in xlsx format for better data analysis.
    │   ├── xml             <- Data in xml format.
    │   └── json            <- Data in Json format for better utilization.
    │
    ├── img                 <- Contains project image files.
    │   
    ├── figures                 <- Graphs generated from the scraped data.
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         			generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── main            <- Contains scripts for automating web scraping using Selenium
    │   │   └── amazon.py
    │   │
    │   ├── visualization   <- Scripts folder for data analysis and visualization
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------
## Methods used:
• Selenium 4.8.3

• Webdriver and Expected Conditions

• System queue, Implicit and Explicit Waits

• Chrome and Chrome Options

• Nested Pagination

• DataFrame Manipulation using Pandas

• Data Storage using CSV, Excel, and JSON format

===========================================================================
