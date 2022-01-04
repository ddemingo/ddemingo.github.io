# README

```sh
$ sudo apt-get install ruby-dev ruby-bundler
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