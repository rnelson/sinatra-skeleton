About
-----
I created this project as a starting point for a Sinatra-based Ruby
project hosted on Heroku. It's probably not the best initial config,
but it's worked for me.

Gems
----
```shell
$ rvmsudo rvm install --default 1.9.3
$ rvmsudo gem install --no-ri mysql pg bundler heroku sass haml liquid
$ bundle install
```

Heroku
------
```shell
$ heroku create --stack cedar
$ git clone git@heroku.com:HEROKUPROJECTNAME.git .
$ heroku addons:add custom_domains:basic
$ heroku domains:add YOURDOMAIN
$ heroku domains:add www.YOURDOMAIN
```