source 'https://rubygems.org'

gem 'rails', '6.0.0.beta3'
gem 'devise'

gem 'sqlite3'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', git: 'https://github.com/rails/jbuilder'
gem 'sdoc', group: :doc
gem 'overcommit'

# ADDED
gem 'warden'

group :development do
  gem 'web-console'
end

group :development, :test do
  gem 'byebug'
  gem 'spring'

  # ADDED ......................................................
  # 3/22/2019: Modified following rspec section.
  gem 'rspec-rails', git: 'https://github.com/rspec/rspec-rails', branch: '4-0-dev'
  gem 'rspec-core', git: 'https://github.com/rspec/rspec-core'
  gem 'rspec-mocks', git: 'https://github.com/rspec/rspec-mocks'
  gem 'rspec-support', git: 'https://github.com/rspec/rspec-support'
  gem 'rspec-expectations', git: 'https://github.com/rspec/rspec-expectations'
  gem 'factory_bot_rails'
  gem 'capybara'
  gem 'spring-commands-rspec'
  gem 'vcr'
  gem 'rubocop-rspec'
end

group :test do
  # ADDED ......................................................
  gem 'webmock'
  gem 'rails-controller-testing'
end
