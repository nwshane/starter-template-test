source 'https://rubygems.org'

#####################################################################
##################### Starter Template Gems #########################

# The framework! :)
gem 'rails', '4.2.2'

# Connection to MySql database
gem 'mysql2', '~> 0.3.18'

# SCSS parsing in asset pipeline
gem 'sass-rails', '~> 5.0'

# CSS and JS compression for production
gem 'uglifier', '>= 1.3.0'

# Makes jQuery available in rails JS
gem 'jquery-rails', '~> 4.0.3'

# Uses caching to improve performance for internal page changes
gem 'turbolinks', '~> 2.5.3'

# JSON creation
gem 'jbuilder', '~> 2.0'

# Stores project secrets in environment variables
gem 'dotenv-rails', '~> 2.0.0'

# Makes compatibility easier for jQuery and turbolinks
gem 'jquery-turbolinks', '~> 2.1.0'

# Makes jQuery UI (like jQuery datepicker) available
gem 'jquery-ui-rails', '~> 5.0.3'

# Simplifies form creation
gem 'formtastic', '~> 3.1.3'

# JavaScript interpreter
gem 'therubyracer', '~> 0.12.1'

# Needed for twitter-bootstrap-rails gem
gem 'less-rails', '~> 2.7.0'

# Bootstrap JS and various bootstrap-related generators/helpers
gem 'twitter-bootstrap-rails', '~> 3.2.0'

# Use formtastic to generate bootstrap-styled forms
gem 'formtastic-bootstrap', '~> 3.1.0'

# Authentication
gem 'devise', '~> 3.4.1'

# Authorization
gem 'cancancan', '~> 1.10.1'

# So that our SCSS can use bootstrap variables
gem 'bootstrap-sass', '~> 3.3.5'

# Useful icons
gem 'font-awesome-sass', '~> 4.4.0'

# Ruby server
gem 'puma', '~> 2.11.1'

# sends updates to google analytics when turbolinks changes page
gem 'google-analytics-turbolinks', '~> 0.0.4'

group :development do
  # Silences assets-related logging
  gem 'quiet_assets', '~> 1.0.3'

  # Recommends SQL query performance optimizations
  gem 'bullet', '~> 4.14.5'

  # Static code analyzer that finds potential security issues
  gem 'brakeman', '~> 3.0.5', require: false

  # Finds unused and missing translations
  gem 'i18n-tasks', '~> 0.8.3'

  # Server-related tasks (such as deploy)
  gem 'mina', '~> 0.3.3', require: false

  # Mina for multiple servers
  gem 'mina-multistage', '~> 1.0.1', require: false
end

group :development, :test do
  # Debugging: write 'binding.pry' in Ruby code to debug in terminal
  gem 'pry-byebug', '~> 3.1.0'

  # Adds a console to application errors in browser
  gem 'web-console', '~> 2.0'

  # Rails app preloader; runs app in background to speed up dev environment
  gem 'spring', '~> 1.3.5'

  # Specification testing
  gem 'rspec-rails', '~> 3.1.0'

  # Adds syntax to check that a collection has a certain number of something
  # Ex: expect(new_user).to have(1).error_on(:role)
  gem 'rspec-collection_matchers', '~> 1.1.2'

  # Easy data creation in tests
  gem 'factory_girl_rails', '~> 4.5.0'

  # Testing API for Rack apps
  gem 'rack-test', '0.6.2'

  # Feature testing
  gem 'capybara', '~> 2.4.4'

  # Can launch browser in case of feature spec errors
  gem 'launchy', '~> 2.4.3'

  # Web driver for feature tests
  gem 'selenium-webdriver', '~> 2.44.0'

  # Tasks screenshots when capybara feature test fails
  gem 'capybara-screenshot', '~> 1.0.4'

  # Cleans database during tests
  gem 'database_cleaner', '~> 1.3.0'

  # Fast web driver with JavaScript support for feature tests
  gem 'poltergeist', '~> 1.7'

  # Feature testing for emails
  gem 'capybara-email', '~> 2.4'

  # Ruby code style
  gem 'rubocop', '~> 0.31.0'
end

#####################################################################
########################## Project Gems #############################
