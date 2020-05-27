source 'https://rubygems.org'
gem "rack", ">= 2.0.6"
gem 'sinatra'
gem 'data_mapper'
gem 'stripe'
gem 'jwt'
gem 'sinatra-namespace'
gem 'activesupport' , '~> 5.2'

group :development do
   gem 'sqlite3', '~> 1.3', '< 1.4'
  gem "dm-sqlite-adapter"
  gem 'rspec'
  gem 'rack-test'
  gem 'capybara', '3.0.0'
  gem 'dm-rspec'
  gem 'rack_session_access'
  gem 'poltergeist'
  gem 'puma'
end

group :production do
  gem 'pg'
  gem 'dm-postgres-adapter'
end
