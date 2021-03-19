# Heroku Review Apps and AutoIdle

This project utilizes Heroku to create review apps for pull requests in GitHub. It also uses AutoIdle to automatically put review apps to sleep when not in use, saving you money.

You can [view the demo here](https://review-apps-and-autoidle.herokuapp.com/) or [read the tutorial here](https://betterprogramming.pub/how-to-create-review-apps-on-heroku-799f548fcc5e?sk=7a5ed5a22afc4dc621a708fb83691c09).

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone https://github.com/thawkin3/heroku-review-apps-and-autoidle.git
$ cd heroku-review-apps-and-autoidle
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create  # or `heroku create <app name>`
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation and Resources

- [Article - How to Create Review Apps on Heroku](https://betterprogramming.pub/how-to-create-review-apps-on-heroku-799f548fcc5e?sk=7a5ed5a22afc4dc621a708fb83691c09)
- [Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Pipelines](https://devcenter.heroku.com/articles/pipelines)
- [Heroku Review Apps](https://devcenter.heroku.com/articles/github-integration-review-apps)
- [Review Apps Management and Costs](https://devcenter.heroku.com/articles/github-integration-review-apps#review-apps-management-and-costs)
- [Using Add-ons in Review Apps](https://devcenter.heroku.com/articles/github-integration-review-apps#environments-in-app-json)
- [AutoIdle Heroku Add-on Docs](https://devcenter.heroku.com/articles/autoidle)
- [AutoIdle Plans and Pricing](https://elements.heroku.com/addons/autoidle)
- [AutoIdle Website](https://autoidle.com/)
