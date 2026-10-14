source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 3.10"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.0"

# The github-pages meta-gem is not used because it pins jekyll-remote-theme
# 0.4.3, which locks rubyzip < 3.0 (path traversal vulnerability). Instead we
# list only the gems this site needs, matching what GitHub Pages provides.
gem "jekyll-theme-tactile", "~> 0.2"
gem "kramdown-parser-gfm", "~> 1.1"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-github-metadata", "~> 2.13"
  # Plugins GitHub Pages enables by default
  gem "jekyll-optional-front-matter"
  gem "jekyll-default-layout"
  gem "jekyll-titles-from-headings"
  gem "jekyll-relative-links"
  gem "jekyll-readme-index"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "kramdown", ">= 2.3.1"
gem "nokogiri", ">= 1.13.4"
gem "activesupport", ">= 6.1.7.1"
gem "faraday-retry"
gem "webrick", ">= 1.8.2"
gem "rexml", ">= 3.2.8"
