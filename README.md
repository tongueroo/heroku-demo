# Test Project for Demo

This project contains a small sinatra app that prints out some text to help demo heroku.  It listens on the default 4567 port locally.

## Testing Locally with Mac OSX

    $ git clone https://github.com/tongueroo/heroku-demo
    $ cd heroku-demo
    $ bundle
    $ ruby hi.rb

## Procfile

There's a [Procfile](Procfile) so deploying to Heroku works.  Follow the Heroku [Deploying With Git](https://devcenter.heroku.com/articles/git) instructions.  Here's the gist of it:

    heroku create
    git push heroku master
