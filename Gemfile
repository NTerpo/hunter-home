source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'rouge'
gem 'github-pages', versions['github-pages']
gem 'jekyll-sitemap'