source 'https://rubygems.org'

# Core gems
gem 'rails', '5.0.0'

# Database adapters
gem 'pg'

# Uncomment next line when using MySQL database
#gem 'mysql2'

# Auth gems
gem 'devise', '>= 4.0.0'
gem 'cancan'

# Server/transport gems
gem 'thin'
gem 'faye'

# Helper gems
gem 'kaminari'
gem 'aws-sdk'
gem 'paperclip'
gem 'remotipart'
gem 'jquery-rails', '>= 4.0.1'
gem 'enumerize'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '>= 5.0.5'
  gem 'coffee-rails', '>= 4.1.1'
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
  gem 'quiet_assets'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'debugger'
end

group :test do
  gem 'faker'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'factory_girl_rails'
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
  gem 'jasmine', '~> 2.0.0'
end
