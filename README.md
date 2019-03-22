# heroku-buildpack-mysql

[![Build Status](https://secure.travis-ci.org/Shopify/heroku-buildpack-mysql.png)](http://travis-ci.org/Shopify/heroku-buildpack-mysql)

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for vendoring the mysql client binaries into your project.

## Versions

* MySQL: `5.7`

## Bug Notice

 This will only copy over `mysqldump` and `mysql` binaries as part of the buildpack for now.
