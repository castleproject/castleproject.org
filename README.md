The Castle Project web site is powered by Jekyll and GitHub Pages.

How to build the site locally:

```shell
# make sure you've got ruby, 1.9.3 or 2.0.0 will do
ruby --version

# install bundler, if you don't already have it
gem install bundler

# install the github-pages package using our Gemfile
bundle install

# start the web server which will keep regenerating the files in _site when you make changes
bundle exec jekyll serve --watch
```

If you run into any problems, check the [GitHub Pages Jekyll documentation][github-pages-doc] first.

[github-pages-doc]: https://help.github.com/articles/using-jekyll-with-pages
