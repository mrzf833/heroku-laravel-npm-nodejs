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

jika masih belum keload itu masalahnya kena cors

tambahkan ini di App\Http\Middleware\TrustProxies.php

protected $proxies = '**';
protected $headers = Request::HEADER_X_FORWARDED_AWS_ELB;
