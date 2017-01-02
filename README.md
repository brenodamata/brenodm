## Running

    bundle install
    thin start

## Heroku 123

    git clone git@github.com:maccman/sinatra-blog.git
    cd sinatra-blog

    heroku create myblog
    heroku labs:enable user-env-compile
    heroku addons:add memcachier:dev

    git push heroku master
