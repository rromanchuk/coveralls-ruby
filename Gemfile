# frozen_string_literal: true

source 'https://rubygems.org'

# Specify your gem's dependencies in coveralls-ruby.gemspec
gemspec

platforms :jruby do
  gem 'jruby-openssl', '~> 0.10.1'
end

platforms :rbx do
  gem 'rubinius-developer_tools', '~> 2.0'
  gem 'rubysl', '~> 2.2'
end

group :development do
  gem 'rake', '~> 12.3'
  gem 'rspec', '~> 3.8'
  gem 'rubocop', '~> 0.66.0'
  gem 'rubocop-rspec', '~> 1.32'
  gem 'truthy', '~> 1.0'
  gem 'vcr', '~> 4.0'
  gem 'webmock', '~> 3.5'
end

group :test do
  gem 'pry', '~> 0.12.2'
end
