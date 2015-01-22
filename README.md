Heroku buildpack: ARJ
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of ARJ compression. This buildpack will install ARJ binary (from ubuntu package) to $PATH

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/alanho/heroku-buildpack-arj.git

# or if your app is already created:
$ heroku config:add BUILDPACK_URL=https://github.com/alanho/heroku-buildpack-arj.git

$ git push heroku master
```