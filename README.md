# Flask_App

This project is based on 'FLASK' a python web development framework written in 'Python'.

## DESCRIPTION

This project mainly concentrates on connecting/manipulating database using flask, by creating `register forms` and `login form` and retriving data as per the given credentials.

> System Requierements
```shell
Python V - 3.4
MySQL Database
```

## Steps for deploying over local server

Clone/Download the repository into your system

> Prerequisite

In order to run the app you must setup a `virtual environment`.
Open `terminal` and go to th directory where the repository is cloned.
```shell
cd … PATH_OF_THE_FILE …
```
### Creating a `Virtual Environment`

```shell
python3 -m venv venv
```
```shell
source venv/bin/activate
```
This will activate the virtual environment for the application.

### Installing the required packages. 
```shell
pip3 install flask
```
```shell
pip3 install flask-bootstrap
```
```shell
pip3 install flask-mysqldb
```
```shell
pip3 install pyyaml
```

After installing the packages you are ready to deploy the application

### Run the application
```shell
python3 app.py
```

### Viewing the deployed application
Open the web browser and navigate to the `local-host` to see the deployed output.
> [Local Host](http://127.0.0.1:5000/)

## Deployed on Heroku
#### [Heroku](https://fierce-brook-79447.herokuapp.com/)
