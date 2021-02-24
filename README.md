# Installing Flask

First we will need to go to Flask's website for installation https://flask.palletsprojects.com/en/1.1.x/installation/#installation 

## Create a project, create an environment, activate the environment
The first step is to create an environment. I used this repository, they suggest typing the following into your terminal:

`mkdir myproject`

`cd myproject`

`python3 -m venv venv`


Since I used this repository, the project was already created, so I just opened the integrated terminal and typed:

`python3 -m venv venv`

Once this environment is created, it needs to be activated:

`. venv/bin/activate`

## Install Flask

Within the activated environment, type the following to install Flask:

`pip3 install Flask`

This will install the current version of Flask. the latest version is available, prerelease by installing or updating the code with a link from GitHub, listed on the installation page under the heading "Living on the Edge"

From here we go to the Quickstart page (https://flask.palletsprojects.com/en/1.1.x/quickstart/) for information on beginning your project.


## Set Up and Running a Flask Project

Set up a file called "hello.py". In that file I entered the following code:

`from flask import Flask `

`app = Flask(__name__)`

`@app.route('/')`

`def hello_world():`

`return 'Autobots, Roll Out!'`

This allowed the return to appear on the development url. 

