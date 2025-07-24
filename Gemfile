# frozen_string_literal: true

source "https://rubygems.org"

# Use GitHub Pages–compatible gem set (keeps versions in sync with Pages)
gem "github-pages", group: :jekyll_plugins

# Chirpy theme
gem "jekyll-theme-chirpy", "~> 7.3"

# Additional plugins
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Platform-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", platforms: [:mingw, :x64_mingw, :mswin]
