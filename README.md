# wkhtmltopdf Buildpack

This is a Heroku buildpack for WKhtmltoPDF binary with your environment. It is compatible with only Heroku Stack 22. 


## Versions

* wkhtmltopdf: `0.12.6`

## Usage


```bash
$ heroku buildpacks:add https://github.com/bigbinary/wkhtmltopdf-buildpack.git
```

### Clearing Repo Cache

Remember to clean your repository cache if you are updating the version of buildpack. To do that, run:

```bash
$ heroku plugins:install https://github.com/heroku/heroku-repo.git
$ heroku repo:purge_cache -a appname
```

