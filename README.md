# Mission-to-Mars
Module 11 Challenge - HTML WebScraping


## Deliverable 1:

The Mars news data was succesfully scraped and added to a list of dictionaries as shown below. 

![dev_1](images/List_of_dict.png "Dictionaries in a list")


## Deliverable 2: 

The Mars news data was succesfully scraped and added to a pandas DataFrame for analysis as shown below.

![dev_2](images/DataFrame.png "DataFrame")

Summary of Data Anlysis Findings:
  1. The data shows there are 12 months that exist on Mars. (Knowing Mar's has about 24 months) We must conclude either the definition for the 'month' variable is incorrect or the data is incomplete. 
  2. The range of days available starts at day 10 and extends until day 1977. So there is a date range of 1967 days of Martian data that exist in the scraped dataset. Also note, the number of samples in the data set is 1867. 
  3. I created a cleaned dataframe to view the min_temp by month. I then plotted this dataframe into a pandas bar chart. The two images are shown below. 
  ![dev_3](images/List of min_temp_table.png "Min_Table")
  ![dev_3](images/List of min_temp_bar.png "Min_bar")
