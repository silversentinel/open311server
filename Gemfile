source 'https://rubygems.org'

gem 'thin'
gem 'sinatra'
gem 'sinatra-contrib'
gem "activerecord"
gem "sinatra-activerecord"

gem 'nokogiri'
gem 'rake'
gem 'json', '~> 1.8.1'
gem 'mechanize'

# Deployment related
gem 'capistrano', '~> 2.15.5'
gem 'rvm-capistrano', '~> 1.3.3'
gem "net-ssh", '=2.7.0'

group :production do
  gem 'pg'
end

group :development do
  gem 'guard', '2.6.1'
  gem 'guard-bundler'
  gem 'guard-rspec'
  gem 'guard-shotgun'
  gem 'guard-rack'
  gem "tux"
end

group :development, :test do
  gem "sqlite3"
  gem 'growl'
end

group :test do
  gem 'rspec'
  gem 'rack-test'
end