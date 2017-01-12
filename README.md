![Jekyll Marlene](images/logo.png)

A minimal template to Jekyll.

## Getting started
- Create a new repo for your project on Github
- In terminal run each line as a separate command

```shell
git clone git@github.com:filipelinhares/jekyll-marlene.git your-project
cd your-project
rm -rf .git
git init
git remote add origin git@github.com:your-name/your-project.git
```

## Deploy

### Heroku
```
git checkout heroku
heroku create your-project --buildpack https://github.com/andycroll/heroku-buildpack-jekyll.git
git push heroku heroku
```

### [Surge](http://surge.sh/help/deploying-a-jekyll-project)

## License
[MIT](LICENSE.md) © Filipe Linhares
