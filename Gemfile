source 'http://rubygems.org'

# rails
gem 'rails', '3.0.5'

# using postgresql as development database
gem 'pg'
gem 'thin'

# Deploying with heroku
# gem 'heroku'

# authentication with devise
gem 'devise'
gem 'cancan'

# Using Jqery JS library
gem 'jquery-rails'

# pagination
gem 'kaminari'

# HAML support
gem 'haml'

group :development do
  # manage heroku environment with heroku_config.yml
  # gem 'heroku-rails'
  # generators for rails 3
  gem 'rails3-generators'
  # HAML support
  gem 'haml-rails'
  gem 'hpricot'
  gem 'ruby_parser'
  # annotate sql models
  gem 'annotate'
end

group :development, :test do
  # generating sample data for tests and development
  gem 'factory_girl_rails'
  gem 'ffaker'
  # bdd with rspec
  gem "rspec-rails", "~> 2.4"
  gem 'fuubar'
  # integration testing with cucumber
  gem 'cucumber-rails'
  gem 'launchy' # So you can do Then show me the page
  gem 'fuubar-cucumber'
  gem 'slowhandcuke'
  # continuous testing with autotest and spork
  gem 'autotest'
  gem 'autotest-notification'
  gem 'spork', '~> 0.9.0.rc'
  # ruby debugger
  gem 'ruby-debug19' if RUBY_VERSION.include? "1.9"
  gem 'ruby-debug' if RUBY_VERSION.include? "1.8"
end
  
group :test do
  #rspec matchers
  gem 'shoulda'
  # browser simulation
  gem 'capybara'
  # clearing the db for testing
  gem 'database_cleaner'
end

