# Development

Install [Bundle](https://bundler.io), and get the site up and running with:

```console
$ bundle install --path _bundle
$ bundle exec jekyll serve
```

# Deployment

Jekyll builds the static version of the site in `_site`. This is currently
deployed with:

```console
$ netlify deploy --prod
```
