# Mission-to-Mars
# Overview
The Mission-to-Mars Challenge involved using different utilities like Python, Flask, PyMongo, Beautiful Soup and Splinter to scrape data from Mars related websites. There are four files provided: Mission_to_Mars_Challenge.ipynb, app.py, scraping.py and index.html. 
First, we write the process how to scrape  Mars’s hemispheres images and images titles in Mission_to_Mars_Challenge.ipynb. In scraping, we add Mars’s hemispheres scrape function and integate the information into scrape_all function. The scraping.py will be imported when we execute app.py to scrape all information we would like to gather. Then render the information in index.html template.

# Website resource
1. https://data-class-mars.s3.amazonaws.com/Mars/index.html
Scrape Mars news. Retrieve news title and paragraph.

2. https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html
Scrap a mars featured image.

3. https://data-class-mars-facts.s3.amazonaws.com/Mars_Facts/index.html
Scrape a mars fact data.

4. https://data-class-mars-hemispheres.s3.amazonaws.com/Mars_Hemispheres/index.html
Scrap a few images of Mars’s hemispheres.

# Some modification in index.html
As you can see, the page pop up is bit urgly. I tried to make sure that I had modify background color and button color.
