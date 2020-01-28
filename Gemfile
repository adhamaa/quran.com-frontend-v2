# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.2.1'

# Use Puma as the app server
gem 'puma', '~> 3.12.1'

# Use SCSS for stylesheets
# gem 'sass-rails', '~> 6.0.0'
# gem 'sassc-rails', '~> 2.1', '>= 2.1.2'

# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '>= 4.2.2'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'

gem 'fast_blank'
gem 'pg'

gem 'jbuilder'
gem 'oj'

# i18n
gem 'translation'

# seo
gem 'canonical-rails', git: 'https://github.com/jumph4x/canonical-rails'
gem 'meta-tags'

gem 'newrelic_rpm'

# For managing cros
gem 'rack-cors', require: 'rack/cors'

gem 'quran-core', github: 'quran/quran-core'

gem 'sentry-raven'

# Pagination
gem 'pagy', '= 3.7.2'

# Cache
gem 'connection_pool'
gem 'dalli'
gem 'dalli-ui', github: 'naveed-ahmad/dalli-ui'
gem 'memcachier'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'binding_of_caller'
  gem 'pry-rails'
  gem 'web-console', '>= 3.3.0'

  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  # gem 'annotate', '= 2.7.4'
  gem 'rails_real_favicon'
  gem 'rubocop', '>= 0.79', require: false
  gem 'rubocop-performance'
  gem 'rubocop-rails', '~> 2.3.2'
  gem 'rubocop-rspec'

  # gem 'spring'
  # gem 'spring-watcher-listen', '~> 2.0.0'

  # Linters
  gem 'scss_lint'
  # Pronto specific gems will analyze code and add comments on Github PR
  gem 'pronto'
  gem 'pronto-blacklist', require: false
  gem 'pronto-brakeman', require: false
  gem 'pronto-erb_lint', require: false
  gem 'pronto-fasterer', require: false
  gem 'pronto-flay', require: false
  gem 'pronto-rubocop', require: false
  gem 'pronto-scss', require: false
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
