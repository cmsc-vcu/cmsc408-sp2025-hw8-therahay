# cmsc408-sp2025-hw8

Homework 8 - World Bank Indicator Analysis

## How the folder is laid out
 ### report folder
 In the report folder you can find the report for the homework. The report is going to be an html and contains all the information about the analysis performed on the World Bank indicators dataset. In the report you can see the different sections of code that we did in SQL to figure out many different kinds of queries. Furthermore, in the report folder there needs to be an env file in order to access the database we are working with. This is important because the env file contains the credentials to access the database. The env file is not included in the repository for security reasons. You can create your own env file by copying the example.env file and filling in the credentials. The env file should look like this:

 ### home directory
 In the home directory you can find that there is a pyproject.toml and this is for the command terminal. If the device has poetry installed it's essential to have this file and in the command prompt to use poetry install in order for all the things needed to render the report.qmd to be viable. 

## How we went about writing the SQL code
I started by looking at the data and trying to figure out what kind of queries the block of code wanted to run. I then wrote the SQL code to perform those queries. We used the SQL code to create views that we could use in our analysis. We then used the views to create the final report. The report is a combination of the SQL code and the analysis we performed on the data. The type of skills that we used were SELECT, JOIN, LIMIT, COUNT, AGGREGATE and many more, a lot of them are within the reports folder.

## What to watch out for
Some of the things I hard time on was making sure I was using the correct database within the report because at times I was using the World data database itself rather than the one I created myself in my own database. Because of this a lot of the queries I did weren't updated like for when I tried to change high income for Venezeula. Another thing to add to that is to remember to always put in the commit keyword when updating the table because it doesn't auto commit and it won't transfer within the table and that made it hard to see unil it was done. 