# README.md

- effective_jekyll is a starter Jekyll site using Bootstrap 4.
- Uses some of the minima files.
- Doesn't use a theme gem.

## Installed Plugins

- [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
- [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)
- [jekyll-deploy-gh-pages](https://github.com/marketplace/actions/jekyll-deploy-gh-pages)
- [jekyll-compress-hmtl](https://github.com/penibelst/jekyll-compress-html)

## Using Bootstrap

- Uses Jquery and Bootstrap CDNs
- Customize Bootstrap via `_sass/bootstrap-4.4.1/_variables.scss`
- Comment out unused components in `_sass/bootstrap-4.4.1/bootstrap.scss`
- Override compiled components in `_sass/componenents/*`

## Sublime Text

- add `_site` and `.jekyll-cache` to your `folder_exclude_patterns` via Preferences --> Settings

## New site setup

1. Clone this repo
2. `bundle install`
3. `bundle exec jekyll serve`
4. Search the folders for REPLACE_ME and update
5. Update the footer h-card contact details for the business or person
