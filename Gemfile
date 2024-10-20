source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.4'

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem 'sprockets-rails'

# Use postgresql as the database for Active Record
gem 'pg', '~> 1.4'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma', '~> 5.0'

# Bundle and transpile JavaScript [https://github.com/rails/jsbundling-rails]
gem 'jsbundling-rails'

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem 'turbo-rails'

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem 'stimulus-rails'

# Bundle and process CSS [https://github.com/rails/cssbundling-rails]
gem 'cssbundling-rails'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'jbuilder'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem 'kredis'

# Add Noticed to support notifications [https://github.com/excid3/noticed]
gem "noticed", "~> 1.5"

# Adding support to View Component (better than partials ;-) ) [https://github.com/github/view_component]
gem 'view_component'

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# Replaced by argon2 and custom authentication solution based on [https://stevepolito.design/blog/rails-authentication-from-scratch/]
# gem "bcrypt", "~> 3.1.7"

# User authentication
# Use Argon2 to hash passwords [https://github.com/technion/ruby-argon2]
gem 'argon2', '~> 2.1.1'

# Export to Excel
# [https://github.com/caxlsx/caxlsx_rails]
# [https://dev.to/yarotheslav/export-from-database-table-to-excel-workbook-level-1-55jd]
gem 'caxlsx'
gem 'caxlsx_rails'

# Adding OAuth2 support [https://github.com/omniauth/omniauth]
gem 'omniauth', '~> 2.1.0'
# Adding Google Sign-in support
gem 'omniauth-google-oauth2' , '~> 1.1.1'
# Required when not using Devise
gem 'omniauth-rails_csrf_protection' 

# Adding Pundit to manage authorizations [https://github.com/varvet/pundit]
gem 'pundit'
# Adding Rolify to manage roles [https://github.com/RolifyCommunity/rolify]
gem 'rolify', '~> 6.0.0'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Mailer - Sendgrid [https://github.com/sendgrid/sendgrid-ruby]
gem 'sendgrid-actionmailer', '~> 3.2.0'

# Sidekiq [https://github.com/mperham/sidekiq]
# gem 'sidekiq', '6.5.5'
gem 'sidekiq', git: 'https://github.com/mperham/sidekiq.git'

# Monitoring - Honeybadger []
gem 'honeybadger', '~> 4.0'

# Use Sass to process CSS
# gem "sassc-rails"

# Nokogiri to parse HTML and more [https://github.com/sparklemotion/nokogiri]
gem 'nokogiri', '~> 1.13.6'

# Download
gem 'down', '~> 5.0'

# Tracking changes using PaperTrail [https://github.com/paper-trail-gem/paper_trail]
gem 'paper_trail'

# Active storage validations [https://github.com/igorkasyanchuk/active_storage_validations]
gem 'active_storage_validations', '~> 0.9.8'

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
gem 'image_processing', '~> 1.2'
gem 'ruby-vips', '>= 2.1.0'
gem 'aws-sdk-s3', require: false


# Generate QRCode [https://github.com/whomwah/rqrcode]
gem 'rqrcode', '~> 2.0'

# Pagination [https://github.com/ddnexus/pagy]
gem 'pagy', '~> 5.10.1'

# Countries [https://github.com/countries/countries]
gem 'countries', '~> 5.1.0', require: 'countries/global'

# Validate URL format [https://github.com/perfectline/validates_url]
gem 'validate_url'

# Tracking
# Ahoy [https://github.com/ankane/ahoy]
gem 'ahoy_matey'

# Group date [https://github.com/ankane/groupdate]
gem 'groupdate'

# Chart [https://chartkick.com]
gem 'chartkick'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', platforms: %i[mri mingw x64_mingw]

  # Faker, gem for generating fake data for testing [https://github.com/faker-ruby/faker]
  gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'master'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'web-console'

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"

  # Add support to Rubocop [https://github.com/rubocop/rubocop]
  gem 'rubocop', '~> 1.30', require: false
  gem 'rubocop-rails', require: false

  # Add support to Brakeman [https://github.com/presidentbeef/brakeman]
  # Vulnerability scanner
  gem 'brakeman'
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end


