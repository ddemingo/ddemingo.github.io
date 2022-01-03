# README

## Install

On Fedora:
```sh
$ sudo dnf module enable ruby:2.7
$ sudo dnf install ruby-devel
```

On Ubuntu:
```sh
TODO
```

Install gems:
```sh
$ bundle config set --local path 'vendor/bundle'
$ bundle install
```

## Develop

Run `jekyll` serve:
```sh
bundle exec jekyll serve --livereload --incremental
```