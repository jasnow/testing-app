source 'https://rubygems.org'

#gem 'rails', '7.0.0'
gem "rails", github: "rails/rails", branch: "7-0-stable"
gem 'devise'
gem 'net-smtp' # Added for Ruby 3.1.

gem 'sqlite3'
gem 'sassc-rails'
gem 'terser'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
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

  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'capybara'
  gem 'spring-commands-rspec'
  gem 'vcr'
  gem 'rubocop-rspec'
end

group :test do
  gem 'webmock'
  gem 'rails-controller-testing'
end
