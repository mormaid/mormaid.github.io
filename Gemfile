# Gemfile
# This tells Bundler which Ruby gems this site needs.
# GitHub Actions will read this file, install these gems, build the Jekyll site,
# and deploy the finished static HTML/CSS to GitHub Pages.

source "https://rubygems.org"

gem "jekyll", "~> 4.3"
gem "jekyll-feed"
gem "jekyll-seo-tag"

# These make SCSS/Sass compilation explicit.
# style.scss should compile into style.css during the Jekyll build.
gem "jekyll-sass-converter", "~> 3.0"
gem "sass-embedded"

# Needed for local Jekyll serving on newer Ruby versions.
# It is harmless in GitHub Actions.
gem "webrick"