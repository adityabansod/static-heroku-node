static-heroku-node
==================

This is a super simple application built to be run on
Heroku to host a static site. Fork (or clone) the repo,
place all your files in the public/ directory and you're done.

If you wish to test it and you have the Heroku toolbelt installed,
start the application with `foreman start` and navigate to
http://localhost:5000/ to see how your site/app will look.

If you're ready to deploy to heroku, simply:

```bash
$ heroku apps:create
$ git push heroku master
$ heroku apps:open
```
