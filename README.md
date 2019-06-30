# Google AppEngine Vue Flask Starter
A simple application for [Google App Engine](https://appengine.google.com/), using [Vue.js](https://vuejs.org/) on the frontend and [Flask](http://flask.pocoo.org/) on the backend.
This project can be deployed on Google AppEngine Python 3.7 Standard Environment.

The frontend was built using the [Vue CLI 3](https://cli.vuejs.org/), and uses [vue-router](https://router.vuejs.org/) and [vuex](https://vuex.vuejs.org/).

If you want, you can empty the /app folder and create a new Vue.js project inside it.

## Install dependencies

Python dependencies:

    pip install -t lib -r requirements.txt

Frontend dependencies (from the app folder):

    npm install

## Local run

Run the Vue.js frontend (from the app folder):

    npx vue-cli-service serve

Run the backend:

    python3 main.py

## Deploy

Build the Vue.js frontend (from the app folder):

    npx vue-cli-service build

Deploy the application on AppEngine:

    gcloud app deploy

## License

[MIT](http://opensource.org/licenses/MIT)
