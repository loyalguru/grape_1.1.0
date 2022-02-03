# when changing this file, run appraisal install ; rubocop -a gemfiles/*.gemfile

source 'https://rubygems.org'

gemspec

group :development, :test do
  gem 'bundler'
  gem 'hashie'
  gem 'rake'
  gem 'rubocop', '0.51.0'
end

group :development do
  gem 'appraisal'
  gem 'benchmark-ips'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-rubocop'
end

group :test do
  gem 'cookiejar'
  gem 'coveralls', '~> 0.8.17', require: false
  gem 'danger-toc', '~> 0.1.2'
  gem 'grape-entity', '~> 0.6'
  gem 'maruku'
  gem 'mime-types'
  gem 'rack-jsonp', require: 'rack/jsonp'
  gem 'rack-test', '~> 0.6.3'
  gem 'rspec', '~> 3.0'
  gem 'ruby-grape-danger', '~> 0.1.0', require: false
end