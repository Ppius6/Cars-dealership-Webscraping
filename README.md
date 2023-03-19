# Web Scraping Cars Sales Website
This project involves scraping a cars sales website using Beautiful Soup and Requests to extract data on cars for sale. The extracted data is then converted into a dataframe using pandas. The aim of the project is to obtain information on the name of the car, mileage, rating, rating count, price, and dealer name.

## Tools and Libraries Used
1. Python 3
2. Beautiful Soup
3. Requests
4. Pandas

## Data Extraction Process
1. The website is scraped using the requests module in Python.
2. The HTML content of the webpage is extracted using Beautiful Soup.
3. The relevant data fields such as name, mileage, rating, rating count, price, and dealer name are identified in the HTML content.
4. The data is then stored in a Pandas dataframe.

## Code Overview
The code is organized as follows:
1. Importing required libraries and modules.
2. Defining the function to scrape the website.
3. Calling the function in a loop to obtain information on multiple cars.
4. Converting the extracted data into a Pandas dataframe.
5. Saving the dataframe as a CSV file.
