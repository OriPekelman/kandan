source 'https://rubygems.org'

# Core gems
gem 'rails', '6.1.7.3'

# Database adapters
gem 'pg'

# Uncomment next line when using MySQL database
#gem 'mysql2'

# Auth gems
gem 'devise', '>= 4.7.1'
gem 'cancan'

# Server/transport gems
gem 'thin'
gem 'faye', '>= 1.1.0'

# Helper gems
gem 'kaminari', '>= 1.2.1'
gem 'aws-sdk', '>= 1.52.0'
gem 'paperclip', '>= 5.2.1'
gem 'remotipart'
gem 'jquery-rails', '>= 4.4.0'
gem 'enumerize'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '>= 5.0.8'
  gem 'coffee-rails', '>= 4.2.2'
  gem 'bourbon'
  gem 'execjs'
  gem 'eco'
  gem 'uglifier', '>= 2.7.2'
  gem 'bootstrap-sass', '~> 3.4.0.0'
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
  gem 'better_errors', '>= 2.8.0'
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
