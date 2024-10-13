# Data_Scrapping_Homework

In this project, Website data is scrapped using BeautifulSoup library in Python.
<br>
website : https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft
<br>

This page contains the information about the Indian aircrafts. We will try to get the details as name of the aircraft, origin, type, variant, no. of services displayed in the html table.
<br>

As shown in ipynb file, all the above mentioned details are fetched using read_html() method of pandas.
Finally, the pandas dataframe is converted into csv file named 'List_of_active_Indian_military_aircraft.csv'.
