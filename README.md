# autotrader-blog-jekyll-theme

This is an Auto Trader branded Jekyll blog theme.

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-remote-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
remote_theme: autotraderuk/autotrader-blog-jekyll-theme
```

And if you want to lock the site to a specific Git ref, you can do it like this:

```yaml
remote_theme: autotraderuk/autotrader-blog-jekyll-theme@v0.1.0
```

or

```yaml
remote_theme: autotraderuk/autotrader-blog-jekyll-theme@mybranch
```

See the [Jekyll Remote Theme](https://github.com/benbalter/jekyll-remote-theme) docs for more.

## Developing

You can serve this like a normal Jekyll site by running `jekyll serve`, and browsing to [http://localhost:4000/](http://localhost:4000/).

You will need to push your changes to GitHub to integrate them with a site which uses this remote theme. Remember that if a site is tied to a specific Git ref of the theme then you’ll need to switch to a branch of the theme, or knock that bit off to see your changes. Once you’re satisfied with your changes then do a release and switch your Git ref to that. 