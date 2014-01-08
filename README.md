About
-----
I created this project as a starting point for a Sinatra-based Ruby
project hosted on Heroku. It's not the best setup (see the
[food inspections](https://github.com/rnelson/ne_state_restaurant_inspections)
project for a better example) but it's enough to get going.

Gems
----
```shell
$ rvm install --default 2.1
$ gem install --no-ri mysql pg bundler heroku sass haml liquid
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
