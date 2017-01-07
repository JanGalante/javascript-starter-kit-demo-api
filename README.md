# js-dev-env-demo-api
API for JS Dev Env Demo in Pluralsight course

2 files specific for Heroku
Procfile - Declare the command that Heroku should run
app.json -  Cconfigure the app for Heroku

## To deploy to Heroku for first time: 
Log you in to heroku (in the root of the project)
```shell
heroku login 
```

Prepare heroku to recieve the app. Generates an url for the app. Its possible to specify your own name
```
heroku create
```

Create a git remote to point to the application. The name/subdomain is the one you got in "heroku create"
```
heroku git:remote -a nameless-shelf-77449
```

publish the app. In the end of the console output you find the url to the app
```git
git push heroku master
```


## Once the first setup is done you just have to...
To push the master branch from git and publish
```
git push heroku master
```

## Other
View existing domains
```
heroku domains
```
Add a custom domain with a subdomain
```
heroku domains:add www.example.com
```
