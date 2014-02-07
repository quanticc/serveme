source 'https://rubygems.org'

gem 'rails', '~> 4.0.0'
gem 'protected_attributes'
gem "actionpack-action_caching"

gem 'haml'
gem 'mysql2'
#For NA
gem 'puma'
gem 'omniauth-openid'
gem 'omniauth-steam'
gem 'devise'
gem 'rubyzip'
gem 'steam-condenser', :github => 'koraktor/steam-condenser-ruby'
gem 'logs_tf'
gem 'sys-proctable',    :require => 'sys/proctable'
gem 'net-ssh-simple'
gem 'net-ssh'
gem 'net-sftp'
gem 'draper'
gem 'will_paginate'
gem 'zeroclipboard-rails'
gem 'cronic'
gem "google_visualr"
gem 'rack-cache'
gem 'paypal-sdk-rest'
gem 'sidekiq'

group :development do
  gem 'better_errors'
  gem 'thin',             :require => false
  gem 'binding_of_caller'

  #Deployment
  gem 'capistrano-ext'
  gem 'capistrano_colors'
  gem 'capistrano', "~> 2.0"
  gem 'capistrano-maintenance'
  gem 'rvm-capistrano'
  gem 'query_reviewer'
end

group :test, :development do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'pry-nav'
  gem 'zonebie'
end

group :test_tools do
  gem 'coveralls', require: false
  gem 'fuubar'
end

group :cucumber do
  gem 'cucumber-rails', :require => false, git: 'https://github.com/cucumber/cucumber-rails.git'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'fuubar-cucumber'
end

group :production do
  gem "sentry-raven"
  gem 'dalli'
end

group :test do
  gem 'shoulda-matchers'
  gem "libv8"
  gem 'vcr'
  gem 'webmock'
  gem 'delorean'
end

gem 'uglifier'
gem 'jquery-rails'
gem "compass-rails", "~> 1.1.2"
gem 'sass-rails'
gem 'bootstrap-sass'
gem 'simple_form'
gem 'will_paginate-bootstrap'
gem 'therubyracer', :require => 'v8'
gem 'font-awesome-rails'
gem 'oily_png'
gem 'coffee-rails'
