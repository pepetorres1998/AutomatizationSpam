#AUTOMATIZATION PROJECT.

This is an automatization project, consist in scrap this [web page](http://www.directorioautomotriz.com.mx/index/), obtaining data from companies, and sending them an email. This project works just with that page, can be improved with Regular Expression. It also generate an excel table with all the data recabed, also an `.txt` with general data of the company.

**This project was tested, but never commercialized**

##Getting Started.

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

###Prerequisites.

You need Python3 in your system.
Also a couple libraries:

1. beautifulsoup4
	-To send emails in an automated way

Install with pip3:
```
pip3 install beautifulsoup4
```

2. requests
	-To make GET request to page.

Install with pip3:
```
pip3 install requests
```

3. openpyxl
	-To make the excel documents.

Install with pip3:
```
pip3 install openpyxl
```

###Installing

Just clone the github to were you want the excel and txt to be placed.

```
git clone https://github.com/pepetorres1998/AutomatizationSpam
```
###Using

Just run ProyectoDirectorioAutomotriz.py in console.

```
python3 ProyectoDirectorioAutomotriz.py
```
THATS IT. THANK YOU FOR READING ^-^

