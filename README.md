This project explores data about Mars using webscraping and analysis. The first part scrapes a Mars news website to extract the titles and
previews of news articles. The second part scrapes a table into a Pandas dataframe for analysis. The Jupyter Notebook for Part 1 uses Splinter
and Beauticul Soup to navigate to a website which contains articles about Mars. An inspection identifies the elements that we want to scrape. 
We then scrape the elements into a Python dictionary. The end of this part is a python dictionary with the titles and previews of articles 
from the site. 

The second part of the project is a Jupyter Notebook that scrapes a table from a website into a Pandas dataframe for analysis. After we have
the table, it must cleaned be and converted so that it can be analyzed. The data needs to be converted from objects into datetime, integer, or float
formats. Once the table is in the correct format, it can be used for analysis. Pandas functions are used to run alnalysis on the temperature
and atmospheric pressure on Mars. Finally, the data is exported into a CSV file. 
