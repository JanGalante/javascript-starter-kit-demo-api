# js-dev-env-demo-api
API for JS Dev Env Demo in Pluralsight course

2 files specific for Heroku
Procfile - Declare the command that Heroku should run
app.json -  Cconfigure the app for Heroku

To deploy to Heroku write in the cmd: 
heroku login (in the root of the project) - Log you in to heroku
heroku create  - Prepare heroku to recieve the app. Generates an url for the app. Its possible to specify your own name
heroku git:remote -a nameless-shelf-77449 - Create a git remote to point to the application. The name/subdomain is the one you got in "heroku create"
git push heroku master - publish the app. In the end of the console output you find the url to the app

When all the above is done once you just have to...
git push heroku master - To push the master branch from git and publish