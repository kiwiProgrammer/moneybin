source 'https://rubygems.org'

group :development do
gem 'rake', '~> 10.4.2'
gem 'compass', '~> 1.0.3'
gem 'sass', '~> 3.4.10'
gem 'jekyll', '~> 2.5.3'
gem 'jekyll-assets'
end

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
