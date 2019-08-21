Lazercube.com
=============

> A Jekyll Project

Quick-start Install:

```shell  
gem install bundler jekyll
bundle install
bundle exec jekyll serve
# => Now browse to http://localhost:4000  
```


# Lazercube.com


## Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/) - Jekyll is a Ruby Gem that so Ruby is needed.
- [Ruby Gems](https://rubygems.org/pages/download) - Package management framework for Ruby.

## Getting started

```shell  
gem install bundler jekyll
bundle install
bundle exec jekyll serve
# => Now browse to http://localhost:4000  
```

## Publishing to github pages

1. `git checkout sources`
1. `jekyll build`, build site
1. `cd _site`, move to site directory
1. `touch .nojekyll`, this file tells gh-pages that there is no need to build
1. `git init`, create new repository
1. `git remote add origin git@github.com:LazerCube/lazercube.github.io.git`
1. `git add -A`, Add site changes
1. `git commit -m "new build"`, commit code
1. `git push origin master`, push to master

## Built With

- [Jekyll](https://jekyllrb.com/) - Static website generator