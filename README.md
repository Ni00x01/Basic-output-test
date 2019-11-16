Check out main fork https://github.com/focalsbynorth/focals-api-quickstart 
# Hopefully the dev portal is working now. 


#heroku Commands: 
$ heroku git:remote -a 'app-name'
$ heroku config:set SECRET_KEY='<your secret key here>' 
$ heroku buildpacks:set heroku/nodejs
$ heroku addons:create heroku-postgresql:hobby-dev
$ heroku addons:create heroku-redis:hobby-dev
$ heroku config:set ALLOWED_HOSTS='<your hosts here>'
$ heroku config:set NODE_MODULES_CACHE=false
$ heroku config:set NPM_CONFIG_PRODUCTION=false
$ heroku config:set SECRET_KEY='<your secret key here>' 

