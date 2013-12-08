source 'https://rubygems.org'

gem 'rails', '3.2.16'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'


gem 'devise',               '~> 2.0.4'

# upgrading to newer versions of these gems caused new github accounts to not be able to
# sign in / create an account on our side
gem 'oauth2',               '~> 0.6.1'
gem 'omniauth-oauth2',      '~> 1.0.2'
gem 'omniauth-github',      '~> 1.0.1'
gem 'unicorn'

group :development, :test do
  gem 'thin',               '~> 1.3.1'
  gem 'pry'
end

group :test do
  gem 'mocha',             '~> 0.10.0'
  gem 'webmock',           '~> 1.7.7'
  gem 'guard'
end

group :development do
  gem 'foreman',            '~> 0.36.0'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
