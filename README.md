# Weather-Data
Scrape the historical weather data from a website, clean and modify the data into a .CSV file and visualize the data.
## Web Scraping
A web scraping program that collects the historical hourly weather including temperature, wind direction & speed, air pressure and visibility for a givin year, stores all the data in a format of raws and each raw has a unique date and hour in a text file named the givin year that has been scraped.
## 2020.text
The scraped file.
## Data Cleansing
Modifying the raw data from 2020.text using regular expression to delete or replace redundant data, measuring units and unwanted data.
measuring units helped in figuring out column names.
and lastly convert the data into a comma separated values file for better handling.
## weather.csv
The cleaned csv file.
## Data Visualization
Using pandas and matplotlib for fast data analysis and plotting the data in various graphical representations in a way that suits the used data.
