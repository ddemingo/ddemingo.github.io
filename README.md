# README

Live demo: [https://david.optersoft.com/smx-8-website/](https://david.optersoft.com/smx-8-website/)

The first project will consist of developing a website that will be hosted on [Github Pages](https://pages.github.com/).


## Getting started

Create a Github account, connect with ssh, and fork this project. To know how to it go to: [Tools/Github](https://github.com/ddemingo/tools/blob/main/github.md)

Create a ubuntu virtual machine with vagrant and use Visual Studio Code with Remote-SSH. To know how to it go to: [Tools/VSCode](https://github.com/ddemingo/tools/blob/main/vscode.md).

Open VSCode terminal, and:

```sh
$ git clone git@github.com:<your-username>/smx-8-website.git # your forked project
$ sudo apt install -y gcc g++ make ruby-bundler ruby-dev 
$ bundle config set --local path 'vendor/bundle'
$ bundle install
$ bundle exec jekyll serve --livereload --incremental
...
    Server address: http://127.0.0.1:4000/smx-8-website/
  Server running... press ctrl-c to stop.
```

Configure git to commit and push to upstream. To know how to it go to: [Tools/Git](https://github.com/ddemingo/tools/blob/main/git.md)

## Develop

TODO!!

[Markdown]. ...

[Github Pages](github-pages.md). With GitHub you can publish your HTML website, and it's free to host there.

[Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll). You can use Jekyll to create a GitHub Pages site in a new or existing repository.
