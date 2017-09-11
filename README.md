# Xsemantics Eclipse Pages

[![Build Status](https://travis-ci.org/bsmith-n4/Xsemantics-www.svg?branch=master)](https://travis-ci.org/bsmith-n4/Xsemantics-www)

Eclipse pages for Xsemantics project.

## Setup

Most site configuration lives in `_config.yml`.

## Develop

These pages are built with [Jekyll](http://jekyllrb.com/). 

Installing the dependencies is done with [Bundler](http://bundler.io/):

~~~bash
$ gem install bundler
$ bundle install
~~~

## Rakefile

the `Rakefile` contains some basic tasks for convenience. 

~~~bash
$ rake build  # generate html to ./_site
$ rake serve  # generate html and serve on localhost
$ rake test   # validate generated html using html-proofer
~~~
