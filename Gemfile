# A sample Gemfile
source "http://rubygems.org"

gem "rails"
gem "mysql2"
gem "savon"

# group :assets do
#   gem 'sass-rails',   '~> 3.1.5'
#   gem 'coffee-rails', '~> 3.1.1'
#   gem 'uglifier', '>= 1.0.3'
# end
# 
# gem 'jquery-rails'

group :development do
  gem 'capistrano'
  gem 'capistrano-ext'
  gem "ruby-debug19", :require => 'ruby-debug'
  gem "rails-footnotes"
end

group :test, :development do
  gem "rspec-rails"
  gem "shoulda-matchers"
  #guard
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-cucumber'
  gem 'guard-bundler'

  gem 'rb-fsevent', :require => false
  gem 'growl', :require => false
  gem 'libnotify', :require => false
  gem 'rb-inotify', :require => false
  gem 'vcr', '~> 2.0.0.rc1'
  gem 'webmock'
end

group :test do
  gem "database_cleaner"
  gem "factory_girl_rails"
  gem 'turn', '< 0.8.3'
end

group :cucumber do
  # gem "capybara"
  gem "cucumber"
  gem 'cucumber-rails'
  gem 'database_cleaner'
  gem 'headless'
  gem 'launchy'
  gem "rack-test"
  # gem 'selenium-webdriver'
  gem 'vcr', '~> 2.0.0.rc1'
  gem 'webmock'
end

# install a Javascript runtime for linux
group :production do
  gem 'therubyracer', '>= 0.9.8'
end
