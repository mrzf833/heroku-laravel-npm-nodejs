# heroku-laravel-npm-nodejs


heroku login

heroku git:remote -a NameApp

heroku buildpacks:add heroku/nodejs

heroku buildpacks

heroku config:set NPM_CONFIG_PRODUCTION=false

"scripts": {
	"postinstall": "npm run production",
    "heroku-postbuild": "npm run production"
}

git push heroku master atau lansung dari heroku tanpa cli yang ini

heroku run npm install
