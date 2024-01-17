# Spotify Python Report
All credit goes to the team as this is a group project with my friends in my second semester at Geogian College for Document Automation with Python course. The developers of this project are Alex, Kevin, Rodrigo and Deep Biswas. It was created over one week and all the developers worked as a team collabrating virtually or in person. 
## How to Run
Download the .py file and the .xlsx file. Put/keep them in same directory and run the .py file. You will see a menu in the terminal which can be used to generate various reports for the spotify songs data (excelsheet). 
Feel free to reach out with any questions or enquiry.
## Dependencies
Please install python 3.12 in order to run the project. You can find the downloads here, https://www.python.org/downloads/ and you can find instructions here, https://wiki.python.org/moin/BeginnersGuid . You also have to install the python modules. To install them paste and run these codes one by one in windows command prompt.
  1. pip install pandas
  2. pip install openpyxl
  3. pip install pyinputplus
  4. pip install matplotlib
  5.pip install xlwings
  6.pip install python-docx
  7.pip install DateTime
  8.pip install time

# Official Documentation
This project is based on an interesting Spotify dataset we found on the page www.kaggle.com provided by the professor Md. Sultan. This dataset was released two months ago as of Dec 2023, and it comes from the Spotify package. Based on all the knowledge that we learned this semester, we focus our analysis in creating different comparisons in the data, regarding genre, artist, songs, energy, danceability, popularity and others that this database provides, to give to the user some recommendations, analysis, graphs and relevant information to help them take the best songs to listen to. The main problem that we found as daily users of Spotify, is when we have too many options on the app and we do not know what playlist to choose or what songs to pick, as a result, sometimes users are bored and always end up listening to the same genre or artist. For this reason, we focus our work on providing to the user’s information to consider at the time to listen to music in the Spotify app.
## Modules/Libraries Used
pandas | openpyxl | pyinputplus | matplotlib | os | xlwings | docx | random | subprocess | datetime | time 
## Description
The project that we created will show to the user a welcome message and then a principal menu with six options:
1. Summary
2. Top 10 most popular songs Report
3. Top 10 most danceable songs Report
4. Top 10 most popular songs of each decade Report
5. Top 10 Artists Report
6. Top 10 workout Songs Report
7. Top genres Report
8. Exit

Our code will display a report for any option that the user chooses and implement bar graphs or graphs in it while exporting. We believe that in addition to creating a file and new table with the data, a chart will increase the view and improve the experience of the user. For this functionality we decided to work with a worksheet to create a general report to show the user what the data is about and its content in the introduction function. Then, top ten most popular songs, top ten most danceable songs, Top 10 most popular songs of each decade report, top ten artists, top ten workout songs, top genres report. We use excel sheet and python libraries to analyze the data. Finally, we believe that the implementation provided will help users make better decisions, to have a general view according to the trend and popularity that the data shows, they can follow our recommendations to decide and enjoy better music themselves.
Thank you.

