source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.6'

group :development, :test do
  gem "toml-rb"
  gem "heroku_hatchet"
  gem "rspec-core"
  gem "rspec-expectations"
  gem "excon"
  gem "rake"
  gem "parallel_tests"
  gem 'rspec-retry'
  gem 'json'
  gem 'ci-queue'
  gem 'redis'
end

gem 'spree', '~> 4.2.1'
gem 'spree_auth_devise', '~> 4.3'
gem 'spree_gateway', '~> 3.9'
gem 'spree_i18n', '~> 5.0'
gem 'sassc', github: 'sass/sassc-ruby', branch: 'master' # only needed for MacOS and Ruby 3.0

