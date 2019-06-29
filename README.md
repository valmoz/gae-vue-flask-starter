# Google AppEngine Vue Flask Starter
A simple application for [Google App Engine](https://appengine.google.com/), using [Vue.js](https://vuejs.org/) on the frontend and [Flask](http://flask.pocoo.org/) on the backend.
This project can be deployed on Google AppEngine Python Standard Environment.

The frontend was built using the [Vue.js Webpack template](http://vuejs-templates.github.io/webpack/), and uses [vue-router](https://router.vuejs.org/) and [vuex](https://vuex.vuejs.org/); vue-router and vuex store are kept in sync using [vuex-router-sync](https://github.com/vuejs/vuex-router-sync).

## Install dependencies

Python dependencies:

    pip install -t lib -r requirements.txt

Frontend dependencies (from the app folder):

    npm install

## Local run

Run the Vue.js frontend (from the app folder):

    npm run dev

Run the backend:

    python3 main.py

## Deploy

Build the Vue.js frontend (from the app folder):

    npm run build

Deploy the application on AppEngine:

    gcloud app deploy

## License

[MIT](http://opensource.org/licenses/MIT)
