# Django React  Webpack Sandbox

## Introduction

This project uses Django for the project's backend and React for the front-end. This project is based off the tutorial by [v1k45](http://v1k45.com/blog/modern-django-part-1-setting-up-django-and-react/).

## Getting started

Create a Python virtualenv using Python 3.X. Then run `pip install -r requirements.txt` from inside the `ponynote` folder.

From the `frontend` folder, run `yarn add` to install the dependencies.

## Running the servers

To run webpack and Django, open two terminal tabs and run `python manage.py runserver` in one from the `ponynote` folder and `node scripts/start.js` from the `frontend` folder in the other terminal window.

In your browser, navigate to `http://localhost:3000`