# automated-deployments
Vercel, Heroku, Netlyfi ...



## Heroku



### Mac:

```bash
brew tap heroku/brew && brew install heroku
```



Set remote and push:

```bash
heroku git:remote -a <yourChosenName>

git push heroku master
```



Build without code changes:

```bash
 git commit -m "moved shared folder"

 git push heroku master
```



### Enviroment:

got to setting in Heroku menu.

If you have a repro with backend and frontend set the Path:

`backend`

and all needed Data from .env like:

```

DATABASE_NAME

DATABASE_TYPE

PORT

PROJECT_PATH

```



Buildpacks:

Perhaps you need and one from the listed links (tbd):

`heroku/nodejs`



### Links:

Build Packs: https://github.com/timanovsky/subdir-heroku-buildpack

Preventing Cool State after 4 h: https://kaffeine.herokuapp.com/





**Date: 2021-10-29**



