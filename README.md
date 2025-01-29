# Personal website of Paolo Gandini
This site is based on the [Just the Docs] theme

#### Update the following files to your own content:
- `index.md` (your new home page)
- `README.md` (information for those who access your site repo on GitHub)

#### Adding a plugin
The Just the Docs theme automatically includes the [`jekyll-seo-tag`] plugin.
To add an extra plugin, you need to add it in the `Gemfile` *and* in `_config.yml`.
For example, to add [`jekyll-default-layout`]:
- Add the following to your site's `Gemfile`:
  ```ruby
  gem "jekyll-default-layout"
  ```
- And add the following to your site's `_config.yml`:
  ```yaml
  plugins:
    - jekyll-default-layout
  ```
#### Publishing your built site on a different platform
Just upload all the files in the directory `_site`.

#### Customization
You're free to customize sites that you create with this template, however you like!
[Browse our documentation][Just the Docs] to learn more about how to use this theme.
