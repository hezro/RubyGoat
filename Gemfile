# frozen_string_literal: true
source "https://rubygems.org"

#don't upgrade
gem "rails", "7.1.0"

ruby "2.5.1"

gem "aruba"
gem "bcrypt"
gem "coffee-rails", ">= 5.0.0"
gem "execjs"
gem "foreman"
gem "jquery-fileupload-rails", ">= 1.0.0"
gem "jquery-rails", ">= 4.3.4"
gem "minitest"
gem "powder" # Pow related gem
gem "pry-rails" # not in dev group in case running via prod/staging @ a training
gem "puma"
gem "rails-perftest"
gem "rake"
gem "responders" , ">= 3.0.0" #For Rails 4.2 # LOCKED DOWN
gem "ruby-prof"
gem "sass-rails"
gem "simplecov", require: false, group: :test
gem "sqlite3"
gem "therubyracer"
gem "turbolinks"
gem "uglifier"
gem "unicorn"

# Add SMTP server support using MailCatcher
# NOTE: https://github.com/sj26/mailcatcher#bundler
# gem 'mailcatcher'

group :development, :mysql do
  gem "better_errors", ">= 2.5.0"
  gem "binding_of_caller"
  gem "brakeman"
  gem "bundler-audit"
  gem "guard-brakeman"
  gem "guard-livereload"
  gem "guard-rspec"
  gem "guard-shell"
  gem "pry"
  gem "rack-livereload", ">= 0.5.1"
  gem "rb-fsevent"
  gem "rubocop-github"
  gem "travis-lint"
end

group :development, :test, :mysql do
  gem "capybara", ">= 3.5.0"
  gem "database_cleaner"
  gem "launchy"
  gem "poltergeist"
  gem "rspec-rails", ">= 3.8.0"
  gem "test-unit"
end

group :mysql do
  gem "mysql2"
end
