

main fork https://github.com/focalsbynorth/focals-api-quickstart 
Some reading  https://focalsbynorth.github.io/focals-api-docs/ 
https://github.com/focalsbynorth/focals-client-js

# Hopefully the dev portal is working now. Or just read the main script like a cave man

Setups for Heroku
```
#heroku Commands setup: node 
$ heroku git:remote -a 'app-name'
$ heroku config:set SECRET_KEY='<your secret key here>' 
$ heroku buildpacks:set heroku/nodejs
$ heroku config:set NODE_MODULES_CACHE=false
$ heroku config:set SECRET_KEY='<your secret key here>' 
```

