source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "github-pages", ">= 232", group: :jekyll_plugins  # 232+ = Jekyll 3.10 / Liquid 4.0.4 (works on Ruby 3.2+)

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'webrick' # required for jekyll serve on Ruby 3.x
  # stdlib gems no longer bundled by default in Ruby 3.4+/4.x
  gem 'csv'
  gem 'base64'
  gem 'bigdecimal'
  gem 'logger'
  gem 'ostruct'
end
