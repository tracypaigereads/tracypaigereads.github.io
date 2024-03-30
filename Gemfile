# frozen_string_literal: true

source "https://rubygems.org"
gemspec
gem 'wdm', '>= 0.1.0' if Gem.win_platform?


#gem "jekyll", "~> 3.9.5"
gem "minima"

group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.12"
  end

#gem "github-pages", "231", group: :jekyll_plugins
#gem "github-pages", group: :jekyll_plugins
gem "jekyll-include-cache", group: :jekyll_plugins


install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
    gem "tzinfo", "~> 1.2"
    gem "tzinfo-data"
  end

gem "webrick", "~> 1.8"