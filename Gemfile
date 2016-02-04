source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'html-proofer'  # travis CI per: http://jekyllrb.com/docs/continuous-integration/
gem 'scss_lint'  # travis CI per: http://jekyllrb.com/docs/continuous-integration/
