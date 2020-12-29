source 'https://rubygems.org'

if ENV["HEROKU"]
  engine, version = *ENV["RUBY_ENGINE"].split("-")
  ruby "1.9.3", :engine => engine, :engine_version => version
end

gem 'rake'
gem 'sinatra'
gem 'multi_json'
gem 'slim'
gem "puma", "~> 3.12.6"
gem 'queue_classic'
gem 'pry'

group :development do
  gem 'foreman', require: false
end
