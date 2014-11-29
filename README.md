# EM Home

A barebones Node.js app using [Express 4](http://expressjs.com/).  It is used to serve up a dummy home page for demonstrating the login function from the EM App, with CORS support.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ git clone git@github.com:rbevers/em_home.git
$ cd em_home
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
