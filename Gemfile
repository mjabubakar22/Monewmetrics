source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.1.0"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima"
# To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!

gem 'ffi', '~> 1.15.5'

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-octicons'
  gem 'jekyll-remote-theme'
  gem "jekyll-twitter-plugin"
  gem 'jekyll-relative-links'
  gem 'jekyll-seo-tag'
  gem 'jekyll-toc'
  gem 'jekyll-gist'
  gem 'jekyll-paginate'
  gem 'jekyll-sitemap'
end

gem "kramdown-math-katex"
gem "jemoji"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

gem "faraday", "< 1.0"

