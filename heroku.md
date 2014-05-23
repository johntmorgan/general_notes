Look at the postgres db:

heroku config --app tl-myflix-stage | grep HEROKU_POSTGRESQL
heroku pg:info --app tl-myflix-stage
