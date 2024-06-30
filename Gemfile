source "https://rubygems.org"

gem "rails", "7.2.0.beta2"
gem "devise"
gem 'net-pop', github: 'ruby/net-pop' # 6/28/2024: Required for RUBY 3.3.3

gem "bigdecimal"
gem "mutex_m"
gem "observer"

gem "sqlite3", "~> 1.4"
gem "sassc-rails"
gem "terser"
gem "jquery-rails"
gem "turbolinks"
gem "jbuilder"
gem "sdoc", group: :doc
gem "overcommit"
gem "webrick"

# ADDED
gem "warden"

group :development do
  gem "web-console"
end

group :development, :test do
  gem "spring"

  gem "rspec-rails"
  gem "factory_bot_rails"
  gem "capybara"
  gem "spring-commands-rspec"
  gem "vcr"
  gem "rubocop-rspec"
  gem "standard"
  gem "ruby_audit"
  gem "spektr"
end

group :test do
  gem "webmock"
  gem "rails-controller-testing"
end

gem 'simplecov', require: false, group: :test
