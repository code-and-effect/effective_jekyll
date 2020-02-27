[![Netlify Status](https://api.netlify.com/api/v1/badges/880b30d7-85fe-413a-92dd-05a3cc64cea3/deploy-status)](https://app.netlify.com/sites/effective-jekyll-demo/deploys)

# Effective Jekyll

This is a starter Jekyll site that uses:

- Bootstrap 4.4.1
- forestry.io as the CMS
- Netlify for the deployment/hosting

Doesn't use a theme gem.

Demo: https://effective-jekyll-demo.netlify.com/

## Installed Plugins

- [jekyll-compress-html](https://github.com/penibelst/jekyll-compress-html)
- [jekyll-feed](https://github.com/jekyll/jekyll-feed)
- [jekyll-menus](https://github.com/forestryio/jekyll-menus)
- [jekyll-paginate-v2](https://github.com/sverrirs/jekyll-paginate-v2)
- [jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from)
- [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
- [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)

## Notes re: Bootstrap 4.4.1

- CDNs for the JS (Jquery, Bootstrap, and Popper) are included at the bottom of `_includes/default.html`
- Customize Bootstrap by editing `_sass/bootstrap-4.4.1/_variables.scss`
- Comment out unused Bootstrap components @included in `_sass/bootstrap-4.4.1/bootstrap.scss`
- Override compiled Bootstrap components in `_sass/componenents/*`

## Notes re: Editor

- Sublime Text: add `_site` and `.jekyll-cache` to your `folder_exclude_patterns` via Preferences --> Settings
- VS.Code: I dunno something similar though :)

## New Site Setup

1. Clone this repo
2. `bundle install`
3. `bundle exec jekyll serve`
4. Search all files for REPLACE_ME and update as appropriate
5. Update the footer h-card contact details for the business or person
6. (optional) Adjust the config.baseurl to "" if deploying to the root of a custom domain
7. Deploy on Netlify using default Jekyll build options

## License

MIT License. Copyright [Code and Effect Inc.](http://www.codeandeffect.com/)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new pull request
