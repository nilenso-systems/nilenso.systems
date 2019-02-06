# Development

Install [Bundle][https://bundler.io], and get the site up and running with:

```console
$ bundle install --path _bundle
$ bundle exec jekyll serve
```

# Deployment

Jekyll builds the static version of the site in `_site`. Just rsync that over
to wherever.

Or better yet, set up CI for the website.
