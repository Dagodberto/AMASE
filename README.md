# AMASE
 
Description:

 "Granmalia" is primarly a GUI based web app for scraping Granma (https://granma.cu/) releases based within a given
timeframe. It was developed modular using Python as main programming language and secondly using SQL (SQLite3) for
creating a local database. The original idea is allowing the user to insert a starting date and a final date so the 
app can save the releases info a local "database.db". 

Python Libraries:

-BeautifulSoup (Web Scraping) 
-Tkinter (Graphical User Interface (GUI))
-SQLite3 (Databases in Python)
 
SQLite:

-Autoincrements tables according to the amount of data python scripts provide
-Includes Date, URL, Id, Article (given the keyword the user looks for)

USE: <pending>

The use is simple, just input a keyword into the search bar and it'll pop up some windows in which the related granma
releases will be shown. After clicking on the articles you shall see the full article.
#Most likely the first version will be a web based app solely for Granma, but scalability is possible and with a less
#tight timeframe I should be able to manage putting a url into the app and scraping no matter which source.

After initializing the app, the scraping process will begin temporarily storing articles inside the data/articles.db
allowing you to isolate these articles within given dates until you close the app.
