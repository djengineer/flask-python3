## Flask-Python3-Starter-Kit 
### by © djengineer 2018
Date updated: 02 April 2018

## Purpose:
This starter kit includes a starting bootstrap jumbotron template using bootstrap-4.0.0, python3.6.2 in the virtual environment. You can check the items installed in the requirements.txt.

This is a basic template to jumpstart lightweight python webapps using the base Flask, or Flask-RESTful if you are creating an api backend.

## This doc includes:
- pip packages
- other files
- venv details
- Setting up system environment in linux OSes
- How to start the local server

## pip packages include:
- Pandas
- Numpy
- flask
- flask-restful
- flask-mongoengine
- flask-mqtt

## Others files:
- Bootstrap 4.0.0-dist 
- Proc file
- requirements.txt

## Venv:
Python 3.6.2 as per the apt-get python3.6 below

## Setting up the system environment to run the virtual environment

If you have python3.6 in your system already, you may skip this part.
However, you may need to install python3.6-venv before you can use the venv that is included in this kit.

For users with using linux os, use the bash script to install python3.6 and python3.6-venv

### Use the following command to activate the venv
```
source venv/bin/activate
```
For windows or other OSes, make sure you have python3.6
## To run the flask server
### If you have a local terminal:
```
python flask_app.py
```
If you want to run the flask-restful, it is best-practice to change the file name to flask_ap.py

Different hosts have different way of starting the app. Please refer to their respective docs for more information.
