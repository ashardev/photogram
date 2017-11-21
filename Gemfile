source 'https://rubygems.org'

gem 'rails', '4.2.7.1'
gem 'figaro', '1.1.1'
gem 'pg', '0.18.4'
gem 'responders', '2.2.0'
gem 'rails-api', '0.4.0'
gem 'active_model_serializers', '0.10.0'
gem 'virtus', '1.0.5'
gem 'state_machines-activerecord'
gem 'acts_as_list', '0.7.4'
gem 'will_paginate'
gem 'humanize'
gem 'counter_culture', '~> 0.1.33'
gem "intercom-rails"
gem 'intercom', "~> 3.5.5"
gem 'sidekiq'
gem 'sidekiq-limit_fetch'
gem 'firebase'
gem 'jira-ruby', require: 'jira-ruby'
gem 'wkhtmltopdf-binary'
gem 'wicked_pdf'

gem 'hellosign-ruby-sdk'
gem 'rest-client'
# Assets
gem 'haml-rails', '0.9.0'
gem 'sass-rails', '5.0.4'
gem 'autoprefixer-rails', '6.3.6.1'
gem 'uglifier', '3.0.0'
gem 'coffee-rails', '4.1.1'
gem 'jquery-rails', '4.1.1'
gem 'angular-rails-templates', '1.0.0'

#Active Admin
gem 'activeadmin', '1.1.0'
# github: 'activeadmin'

# Authentication & Authorization
gem 'cancancan', '1.14.0'
gem 'devise_token_auth', '0.1.37'
# Validation
gem 'validates_timeliness', '4.0.2'

# Seed data
gem 'factory_girl_rails', '4.7.0'
gem 'faker', '1.6.3'

# File uploading and storage
gem 'carrierwave', '0.11.2'
gem 'carrierwave-aws', '1.0.1'
gem 'mini_magick',      '3.8.0'

# Scheduling and background jobs
gem 'whenever', require: false

# in-line css formating of emails
gem 'roadie-rails', '1.1.1'

# Bug/error reporting
gem 'bugsnag'

# Datadog tracing gem
gem 'ddtrace'

# New relic
gem 'newrelic_rpm'

# Google authentication/sign in
gem 'omniauth'
gem 'omniauth-oauth2', '~> 1.4.0'
gem 'omniauth-google-oauth2'
gem 'chilkat', '9.5.0.65'

# Bamboo HR integration
gem 'bamboozled'

# HTTP
gem 'http'

# Namely integration
# gem 'namely'

# City-States
gem 'city-state'
gem 'country_state_select'
gem 'countries'

# Algolia
gem 'algoliasearch-rails'

gem 'phonelib'

# ADP Workforce-now integration
gem 'oauth'
gem 'adp-connection'

# g-suite integration
gem 'google-api-client'

# feature flagging
gem 'splitclient-rb', '~> 4.3.0'
gem 'splitapi-rb'

# iCalendar
gem 'icalendar', '~> 2.4', '>= 2.4.1'

# Encryption
gem "attr_encrypted", "~> 3.0.0"

# Frontend
source 'https://rails-assets.org' do
  gem 'rails-assets-angular', '1.5.6'
  gem 'rails-assets-angular-resource', '1.5.6'
  gem 'rails-assets-angular-sanitize', '1.5.6'
  gem 'rails-assets-angular-ui-router', '0.3.0'
  gem 'rails-assets-ng-token-auth', '0.0.27'
  gem 'rails-assets-moment', '2.13.0'
  gem 'rails-assets-browser'
  gem 'rails-assets-angular-environment'
  gem 'rails-assets-parsleyjs'
  gem 'rails-assets-ng-csv'
  gem 'rails-assets-angular-material'
  gem 'rails-assets-angular-cookies'
  gem 'rails-assets-angular-messages'
  gem 'rails-assets-mobile-detect'
  gem 'rails-assets-perfect-scrollbar'
  gem 'rails-assets-datatables'
  gem 'rails-assets-datatables.net'
  gem 'rails-assets-datatables-responsive'
  gem 'rails-assets-angular-datatables'
  gem 'rails-assets-ngtouch'
  gem 'rails-assets-ng-sortable', '1.3.6'
  gem 'rails-assets-rangy'
  gem 'rails-assets-dropify'
end

# To make zip files using Rubyzip
gem 'rubyzip'

# To get files from aws HTTParty
gem  'httparty'

# Internationalization
gem 'i18n-js', '>= 3.0.0.rc11'

# To parse XML response returned by initial SAML request
gem 'nokogiri'

# SAML AUTHENTICATION
gem 'ruby-saml', :github => 'onelogin/ruby-saml'

# Scan File
gem 'clamby'

group :development, :test do
  gem 'thin', '1.7.0'
  gem 'byebug', '9.0.5'
  gem 'awesome_print', '1.6.1'
end

group :development do
  gem 'web-console', '2.3.0'
  gem 'spring', '1.7.1'
  gem 'letter_opener', '1.4.1'
  gem 'brakeman', :require => false

  # Deployment
  gem 'capistrano', '3.5.0', require: false
  gem 'capistrano-rails', '1.1.6', require: false
  gem 'capistrano-sidekiq', require: false
  gem 'capistrano-bundler', '1.1.4', require: false
  gem 'rvm1-capistrano3', '1.4.0', require: false
end

group :test do
  gem 'rspec-rails', '3.4.2'
  gem 'database_cleaner', '1.5.3', require: false
  gem 'shoulda-matchers', '3.1.1', require: false
  gem 'fuubar', '2.0.0', require: false
  gem 'capybara', '2.7.1'
  gem 'poltergeist', '1.9.0'
  gem 'selenium-webdriver'
  gem 'capybara-screenshot', '1.0.13'
  gem 'email_spec', '2.1.0'
  gem "simplecov"
  gem "codeclimate-test-reporter", "~> 1.0.0"
end

group :staging, :production, :demo do
  gem 'puma', '3.4.0'
end
