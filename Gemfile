ruby '2.6.2' # Release date: 2018-10-18
source 'https://rubygems.org'

# Production requirements
gem 'require_all', '~> 2.0.0'
gem 'sinatra', '~> 2.0.7'
gem 'slim', '~> 4.0.1'
gem 'tilt', '~> 2.0.9'

# Testing and metrics (not necessary in production)
group :test do
  gem 'codecov',   '~> 0.1.15', require: false
  gem 'minitest',  '~> 5.11.1'
  gem 'rack-test', '~> 1.1.0'
  gem 'rake',      '~> 13.0.0'
  gem 'rspec',     '~> 3.9.0'
  gem 'simplecov', '~> 0.17.1', require: false

  # YAML files in data/* syntax validator
  gem 'yaml-lint', '~> 0.0.10'
end
