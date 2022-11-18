# frozen_string_literal: true

source "https://rubygems.org"

#
## RUBY VERSION
#
ruby "3.1.2"

#
## SERVER
#
gem "puma"

#
## RAILS
#
gem "rails", "< 7.1"

#
## DATABASE
#
gem "mysql2"

#
## ASSETS
#
gem "cssbundling-rails"
gem "importmap-rails"
gem "propshaft"
gem "stimulus-rails"
gem "turbo-rails"

#
## LIBRARIES
#
gem "bootsnap", require: false

#
## DEVELOPMENT
#
group :development do
  gem "rubocop", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rake", require: false
  gem "web-console"
end

#
## DEVELOPMENT & TEST
#
group :development, :test do
  gem "debug"
end
