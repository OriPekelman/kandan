source 'https://rubygems.org'

# Core gems
gem 'rails', '3.2.14'

# Database adapters
gem 'pg'

# Uncomment next line when using MySQL database
#gem 'mysql2'

# Auth gems
gem 'devise', '>= 2.2.3'
gem 'cancan'

# Server/transport gems
gem 'thin'
gem 'faye'

# Helper gems
gem 'kaminari', '>= 0.14.1'
gem 'aws-sdk'
gem 'paperclip', '>= 3.4.1'
gem 'remotipart'
gem 'jquery-rails', '>= 2.2.1'
gem 'enumerize', '>= 0.5.1'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '>= 3.2.6'
  gem 'coffee-rails', '>= 3.2.2'
  gem 'bourbon'
  gem 'execjs'
  gem 'eco'
  gem 'uglifier'
  gem 'bootstrap-sass', '~> 2.3.0.1'
  gem 'gemoji'
end

group :production do
  gem 'kandan-count'
end

group :development do
  gem 'kandan-count-dev'
  gem 'pry-rails'
  gem 'quiet_assets', '>= 1.0.2'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'debugger'
end

group :test do
  gem 'faker', '>= 1.1.2'
  gem 'rspec-rails', '>= 2.13.0'
  gem 'shoulda-matchers', '>= 1.5.6'
  gem 'factory_girl_rails', '>= 4.2.1'
  gem 'simplecov', :require => false
  gem 'coveralls', :require => false

  gem 'poltergeist'
  gem 'launchy'
  gem 'capybara'
end

group :development, :test do
  gem 'sqlite3'
  gem 'guard'
  gem 'guard-rspec'
  gem 'database_cleaner'
  gem 'jasmine', '~> 1.3.1'
end
