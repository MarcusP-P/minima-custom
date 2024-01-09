# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"

group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.17.0'
  gem 'jekyll-seo-tag', '~> 2.8'
  gem 'jekyll-last-modified-at', '~> 1.3'
end

