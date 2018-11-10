source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
#gem 'json', '~> 2.1'
#gem 'json'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
gem 'shoulda', '~> 3.6'
gem 'date_validator', '~> 0.9.0'
gem 'foreigner', '~> 1.7', '>= 1.7.4'
gem 'will_paginate', '~> 3.1', '>= 3.1.6'
gem 'will_paginate-bootstrap', '~> 1.0', '>= 1.0.1'
gem 'searchkick', '~> 3.1', '>= 3.1.2'
gem 'money', '~> 6.13', '>= 6.13.1'
gem 'money-rails', '~> 1.13'
gem 'elasticsearch-model', '~> 6.0'
gem 'elasticsearch-rails', '~> 6.0'
gem 'geocoder', '~> 1.5'
gem 'geo_ip', '~> 0.7.1'
gem 'stripe', '~> 3.30'
gem 'wkhtmltopdf-binary', '~> 0.12.4'
gem 'wicked_pdf', '~> 1.1'
gem 'premailer-rails', '~> 1.10', '>= 1.10.2'
gem 'nokogiri', '~> 1.8', '>= 1.8.5'
gem 'acts_as_votable', '~> 0.12.0'
#gem 'aws-sdk-v1', '~> 1.67.0'
gem 'carrierwave', '~> 1.2', '>= 1.2.3'
gem 'fog', '~> 2.0.0', '>= 2.0.0'
gem 'figaro', '~> 1.1', '>= 1.1.1'
gem 'mini_magick', '~> 4.9', '>= 4.9.2'
gem 'responders', '~> 2.4'
gem 'devise', '~> 4.5'
gem 'elastic-beanstalk', '~> 1.2', '>= 1.2.2'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.4'
gem 'mail_form', '~> 1.7', '>= 1.7.1'
gem 'simple_form', '~> 4.0', '>= 4.0.1'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 3.8', '>= 3.8.1'
  gem 'rspec-its', '~> 1.2'
  gem 'simplecov', '~> 0.16.1', :require=> false
  gem 'guard-rspec', '~> 4.7', '>= 4.7.3'
  #gem 'spork-rails', '~> 3.3.0', '>= 3.3.0'
  gem 'guard-spork', '~> 2.1', '>= 2.1.0'
  gem 'childprocess', '~> 0.9.0'
  gem 'rails-erd', '~> 1.5', '>= 1.5.2'
  gem 'pry-rails', '~> 0.3.7'
  gem 'guard-rails', '~> 0.8.1'
  gem 'guard-livereload', '~> 2.5', '>= 2.5.2'
  gem 'guard-bundler', '~> 2.1'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'factory_girl_rails', '~> 4.9'
  gem 'faker', '~> 1.9', '>= 1.9.1'
  gem 'launchy', '~> 2.4', '>= 2.4.3'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
