# FacebookScraper
This script scrapes posts and comments from facebook pages and store its with their details in mysql databases .

# Requirements
This script test under this Requirements
  1- Ubuntu OS.
  2- Python [ installed already with ubuntu ] .
  3- MySQL Server .
      install it by this command
            	$ apt-get install mysql-server

# Setup Script
  1- Download Script .
	    	$ git clone https://github.com/atbero/FacebookScraper.git
  2- Create Database fb_data
		$ mysql -u root -p
		mysql> CREATE DATABASE fb_data;
  3- Import Database structure .[ Use /database/fb_dta.sql ].
		$mysql -u root -p fb_data < /database/fb_data.sql
  4- Edit Script vars to fit your data.
  5- Run Script :)
		$python -W ignore script.py
