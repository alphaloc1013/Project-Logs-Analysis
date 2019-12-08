# Project-Logs-Analysis
Reporting tool that prints out reports

## Getting Started

This project queries a news database to obtain the solutions for the following questions:

1. What are the most popular three articles of all time?
2. Who are the most populare article authors of all time?
3. On which days did more than 1% of requests lead to errors?

### Prerequisites

Some experience with using puthon3, virtualbox and postgresql

### Files
* **report.py** contains the python code
* **result.txt** contains the result of an run
* **Readme.md** contains readme file

### Installing

Via terminal **cd** into the folder where the report.py project is located

1. Install Virtualbox and Vagrant
2. Run **Vagrant up** to start VM
3. Run **Vagrant SSH** to verify it is running
4. Install python3 and psycopg2
5. Run **psql -d news -f newsdata.sql** to load and validate the news database
6. Run **python report.py** to see the project results

## Authors

Anthony Moore
