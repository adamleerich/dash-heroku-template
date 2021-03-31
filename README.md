
# Dash Hello World

This app is running at https://lit-earth-51943.herokuapp.com/.


## Setting up a new project

1. Create a new repo using this as a template
2. Clone locally
3. Run the following Heroku CLI commands to get it linked up
   * `heroku login`
   * `heroku create`
   * `git push heroku main` (or `master`)
   * `heroku ps:scale web=1` (assign one dyno to the app)
   * `heroku open` (opens the app on Heroku)
4. Develop
5. Test the app locally: `heroku local -f Procfile.windows`
6. Deploy changes
   * `git push heroku main` (or `master`)
   * `heroku open` (opens the app on Heroku)



## Links
* Plotly main page: https://plot.ly/
* Dash documentation: https://plot.ly/dash
* Dash gallery: https://plot.ly/dash/gallery



## Source 

This template repo started as a fork of https://github.com/plotly/dash-hello-world.
I followed these tutorials to get it up and running on Heroku:

* https://towardsdatascience.com/deploying-your-dash-app-to-heroku-the-magical-guide-39bd6a0c586c
* https://devcenter.heroku.com/articles/getting-started-with-python

