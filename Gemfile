source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.2", ">= 7.0.2.4"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "jbuilder"
gem "redis", "~> 4.0"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem "sassc-rails"
gem "faraday"
gem "faraday-retry"
gem "faraday-gzip"
gem "faraday-follow_redirects"
gem "sidekiq"
gem "sidekiq-unique-jobs"
gem 'sidekiq-status'
gem "bibliothecary"
gem "pghero"
gem "pg_query"
gem 'bootstrap'
gem "rack-attack"
gem "rack-attack-rate-limit", require: "rack/attack/rate-limit"
gem 'rack-cors'
gem 'rswag-api'
gem 'rswag-ui'

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end

group :test do
  gem "shoulda"
  gem "webmock"
  gem "mocha"
  gem "rails-controller-testing"
end
