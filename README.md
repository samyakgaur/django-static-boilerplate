# Django Project Boilerplate [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![Build Status](https://travis-ci.com/samyakgaur/django-static-boilerplate.svg?branch=master)](https://travis-ci.com/samyakgaur/django-static-boilerplate)

This repository is a boilerplate Django project for quickly getting started.

## Getting started

Steps:

1. Clone/pull/download this repository
2. Use of virtualenv is suggested because it wont install dependencies on your machine, Run `pip install virtualenv`
  * #### For macOS/Linux
     ```
     virtualenv venv
     source/bin/activate
     pip install -r requirements.txt
     ```
   * #### For Windows
     ```
     virtualenv venv
     venv\Scripts\activate
     pip install -r requirements.txt
     ```
3. Configure your .env variables
4. Rename your project with `python manage.py rename <yourprojectname> <newprojectname>`

This project includes:
1. Django commands for renaming your project and creating a superuser
2. A cli tool for setting environment variables for deployment.
