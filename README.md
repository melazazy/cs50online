# Craftsmen Website
#### Video Demo:  https://www.youtube.com/watch?v=261kRLrtWcQ

#### Description:


## Table of Contents
1. [General Info](#general-info)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Technologies](#technologies)
5. [Files](#files)
6. [IMAGES](#img)
7. [How to use Site](#site)

### General Info
***
#### The site visitor can register As Craftsman Or As a Client or participate on the site as a visitor

### Requirements
***
_The Project don't need special requirements Just Flask And some Liblary in Setup Section_

### Installation
***
- **Create Project Folder:**
    -  copy All File(s) in Directory:
      - Active Flask venv
	- > `. venv/bin/activate` For mac
	- Run Application Use Command:-
	- > ` flask run `

### Technologies:-
***
### Front-end :-
_Using Bootstrap , jquery and Some of own CSS_

### Backend :-
- PYTHON /Flask
- SQLite 3
- Javascript



### Files & directories
***
- venv
- __pycache__
- static
	- style
		- customstyle file
		- normalize file
		- bootstrap file
	- JS
		- custom script
		- Bootstrap Files
		- sort file
	- images files
- templates
	- index.html, layout.html, search.html for Base
	- login.html, register.html
	- add_request , clprofile, services for Clients
	- add_service , crprofile, requests for Craftsman
- main app files and database:-
	- app.py "main File"
	- crafts.db  Database
	- module,helper.py


###############3
Structure
note: there are some prepared files in static and templates folder to make a simple view.

# 1)Craftsman:-
	- register
	- login
	- logout
	- Add Service
	- Search For Requests
	- Accept Request
	- Reject Request
	- Edit Profile

# 2)client:-
	- register
	- login
	- logout
	- Add Request
	- Search For Services
	- Accept Service
	- Reject Service
	- Edit Profile
# 3)Guest:-
	-Search For Services
	-Search For Requests


### How to use a Site:-
***
- 1 registering as a craftsman:

	- You Can Register As Craftsman

	- You can Add Services You Can Do And Accept Work Requests From The Client
	-  after log in:-
		- add some services.
		- Go to Profile Page
	- Here the services that You offer appear, and if anyone has requested your Services,
	- and it is possible to modify my profile data.
	- Through the search page:
	- Search for required services that  can do in your free time

-2 registering as a Customer
	- You Can Register As customer
	- You can Add Requests for Work you need to do with a Special craftsman
	- after log in:-
	- add Any Requests You Want
	- Go to Profile Page
	- Here the requests that I present appear, and if anyone has agreed to one of my requests,o
	- Through the search page, I can search for offered services that suit my needs

#  As for the visitor
#### the visitor can only go to the search page and find out only the offered and required services.
### but can't contact any user or ask for any request.
 #### what I used in this Web Application :-
### CS50 SQLite library
### flask framework for python
###  bootstrap library
### HTML ,CSS,  javascript,

### Waiting to do
	contact operations
	route optimization
	add paypal process
	add google+ login process
	page for Approved Services
	page for Approved Requests
	Google API For Places


### Change log
	add the test module and fix some details
	add a salted session choice
	add a simple pagination


## Credits
_Mustafa Elazazy_

