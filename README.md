# node-web-server

A Node js application to deploy using heroku.

#Running Locally

Make sure you have [Node.js](http://nodejs.org/),  [handlebars.js](http://github.com/wycats/handlebars.js) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
git clone git@github.com:FRedRick97/node-web-server # or clone your own fork
cd node-web-server
npm install
npm start
```
Your app should be running locally on [localhost:3000](http://localhost:3000).

#Deploying to Heroku

```
heroku create
git push heroku master
heroku open
```
