# Code of Conduct 

Published: [Code of Conduct](http://railsbridge.github.io/code-of-conduct/)

# TO DO

* Add License file (proposal sent to list for review)
* Add links
* Add Contact Info


# Editing Instructions

We're using the [github-pages gem](https://github.com/github/pages-gem/blob/master/github-pages.gemspec#L16) to ensure we're using locally the same versions of gems that github uses when we publish. 

```
git branch --track gh-pages origin/gh-pages
bundle install
```

Edit markdown files at the root directory or functional/visual design in _layouts, javascripts, stylesheets.  Do not directly edit anything in _sites

To view the site locally:
```
jekyll serve
```


