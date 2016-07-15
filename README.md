# Deploy Your Own REST API in 30 Mins Using mLabs and Heroku

## Requirements

* [Node.js](http://nodejs.org/)
* [Heroku Account](https://signup.heroku.com/)
* [Heroku Toolbelt](https://toolbelt.heroku.com/)
* [mLab account](https://mlab.com/signup/)

## Installation

1. Clone repo
2. Run `heroku create`
3. Run `npm install`
4. Create a new single-node Sandbox MongoDB database in US EAST
5. Set `MONGOLAB_URI` env var on Heroku
6. Run `git push heroku master`
7. Run `heroku ps:scale web=1`
8. Run `heroku open`

