ruby '2.0.0'
source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use sqlite3 as the database for Active Record
gem 'sqlite3', group: [:development, :test]
gem 'pg', group: [:production]

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
gem 'debugger', group: [:development, :test]
gem 'restforce'
gem 'vcr_cable', '>= 0.2.3'

group :development, :test do
  gem 'rspec-rails', '~> 2.0'
  gem 'spork', :github => 'sporkrb/spork'
  gem 'spork-rails', :github => 'sporkrb/spork-rails'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'terminal-notifier-guard'
  gem 'pry-rails'
  gem 'rubocop', '~> 0.29.1'
end

group :test do
  gem 'shoulda-matchers'
end

gem 'dotenv-rails', :groups => [:development, :test]
gem 'mocha', require: false
gem 'timecop'
gem 'normalize-rails'
gem 'rails_12factor', group: :production # Heroku wank
gem 'roadie' # Inline styles etc. for emails
gem 'webmock', group: :test
gem "mail_view", "~> 1.0.3"
gem "factory_girl_rails", "~> 4.0"

