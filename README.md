About
-----
I created this project as a starting point for a Sinatra-based Ruby
project hosted on Heroku. It's probably not the best initial config,
but it's worked for me.

Gems
----
$ gem install bundler
$ gem install heroku
$ gem install sass    
$ gem install --no-ri haml
$ gem install liquid
$ bundle install

Heroku
------
$ heroku create --stack cedar
$ git clone git@heroku.com:HEROKUPROJECTNAME.git .
$ heroku addons:add custom_domains:basic
$ heroku domains:add YOURDOMAIN
$ heroku domains:add www.YOURDOMAIN