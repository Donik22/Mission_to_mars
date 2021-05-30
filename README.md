# Mission_to_mars

## Overview
Scrapping Data mars data from multiple websites and compiling it into one website to be accessed by the web app. The polished result will include a button to scrape new data including a table of multiple images of the mars hemisphere from the source. 
note: Scrapping-friendly websites were used for this analysis.

## Sources

Websites  : 
- https://data-class-mars.s3.amazonaws.com/Mars/index.html
- https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html
- https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars

Software : 
- Python 3.9.4 
- anaconda 1.7.2 
- git version 2.30.1.windows.1
- Microsoft Edge Version 91.0.864.37 (Official build) (64-bit)

Python libraries such as `pandas`, `splinter` , `BeautifulSoup`, `datetime`, `scraping`, `flask` , `pymongo` and `ChromeDriverManager` were also used.

## Summary and Results

The result of the data scraping can be accessed after by running The [app.py folder](https://github.com/Donik22/Mission_to_mars/blob/main/app.py) given that the rest of the files in this repository are downloaded as is. The website shows a scraping button that when pushed will use splinter to automate scraping and present us with the new/updated version of the website. The website includes images of four mars hemispheres and a table with information about the red planet relative to earth.
