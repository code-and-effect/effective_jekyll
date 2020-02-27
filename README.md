# Effective Jekyll

- effective_jekyll is a starter Jekyll site using Bootstrap4 and forestry.io
- Doesn't use a theme gem. Sites built with effective_jekyll are assumed to be custom and/or not wanting to pull changes from a gem.
-

## Installed Plugins

- [jekyll-compress-html](https://github.com/penibelst/jekyll-compress-html)
- [jekyll-feed](https://github.com/jekyll/jekyll-feed)
- [jekyll-menus](https://github.com/forestryio/jekyll-menus)
- [jekyll-paginate-v2](https://github.com/sverrirs/jekyll-paginate-v2)
- [jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from)
- [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
- [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)

## Deployment

Configured to deploy on GitHub pages via [jekyll-deploy-gh-pages](https://github.com/marketplace/actions/jekyll-deploy-gh-pages)

## Bootstrap 4.4.1

- CDNs for the JS (Jquery, Bootstrap, and Popper) are included in `_includes/default.html`
- Customize Bootstrap4 by editing `_sass/bootstrap-4.4.1/_variables.scss`
- Comment out unused Bootstrap4 components @included in `_sass/bootstrap-4.4.1/bootstrap.scss`
- Override compiled Bootstrap4 components in `_sass/componenents/*`

## Sublime Text

- add `_site` and `.jekyll-cache` to your `folder_exclude_patterns` via Preferences --> Settings

## New Site Setup

1. Clone this repo
2. `bundle install`
3. `bundle exec jekyll serve`
4. Search all files for REPLACE_ME and update as appropriate
5. Update the footer h-card contact details for the business or person
6. (optional) Copy CNAME.example to /CNAME
7. (optional) Adjust the config.baseurl to "" if deploying to the root of a custom domain

## License

MIT License.  Copyright [Code and Effect Inc.](http://www.codeandeffect.com/)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new pull request
