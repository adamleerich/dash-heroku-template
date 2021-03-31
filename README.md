
# Dash Hello World

This template repo started as a fork of https://github.com/plotly/dash-hello-world.
I followed these tutorials to get it up and running on Heroku:

* https://towardsdatascience.com/deploying-your-dash-app-to-heroku-the-magical-guide-39bd6a0c586c
* https://devcenter.heroku.com/articles/getting-started-with-python


## Setting up a new project

1. Create a new repo using this as a template
2. Clone locally
3. Run the following Heroku CLI commands to get it linked up

     a. `heroku login`
     b. `heroku create`
     c. `git push heroku main` (or `master`)
     d. `heroku ps:scale web=1` (assign one dyno to the app)
     e. `heroku open` (opens the app on Heroku)

4. Develop
5. Test the app locally: `heroku local -f Procfile.windows`
6. Deploy changes

     a. `git push heroku main` (or `master`)
     b. `heroku open` (opens the app on Heroku)



## Links
* Plotly main page: https://plot.ly/
* Dash documentation: https://plot.ly/dash
* Dash gallery: https://plot.ly/dash/gallery





