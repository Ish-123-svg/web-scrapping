# web-scrapping

Problem:

Process the webpages in the given sites to extract the given information below to create an index table in a SQL Server. You can choose any script language for this lab – Python, Java Script, PHP, or any language to scarp the following webpage to create a table in a SQL Server from the contents in the webpage as follow.

Answer:

I have used Python language for the web scrapping. And MS SQL as 

Workflow:-
•	With python, I am extracting the each president name, data from the URl 'http://cis.csuohio.edu/~sschung/CIS593/SimplifiedInfoUnionAddress.htm'
•	After getting details each president related html tag. I am splitting the data accordingly to get the president name and date.
•	Once we got the president details, we can get the president related link  as “https://www.infoplease.com/homework-help/us-documents/state-union-address-firstname-lastname-month-day-year”. Here  firstname, lastname,month,day and year details vary for each present and we already got these details in previous process.
•	The text present in each president related link is also fetching from each site.
•	All the details fetched are saved into csv file with columns as Name of President, Date of Union Address, Link to Address, Filename_Address and Text of Address. Here the Filename_Address is the path of the text file where the president details are saved for our future purpose.
•	I have also created the Database President and table president_data and inserted the details into table within the python code
