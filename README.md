# README


Fedora:
```sh
sudo dnf module enable ruby:2.7
sudo dnf install ruby-devel
```

Install gems:
```sh
bundle config set --local path 'vendor/bundle'
bundle install
```

Update:
```sh
bundle update github-pages.
```