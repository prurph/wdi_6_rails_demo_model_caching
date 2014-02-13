source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# Use postgresql as the database for Active Record
gem 'pg'

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

gem 'newrelic_rpm'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

gem 'dotenv-rails'
gem 'time_difference'

group :production do
  gem 'rails_12factor'
end

group :development do
  # Add model attributes
  gem 'annotate'

  # help to kill N+1 queries and unused eager loading
  # https://github.com/flyerhzm/bullet. Needs config in development.rb
  gem 'bullet'

  # https://github.com/plentz/lol_dba
  # list columns that should be indexed
  gem 'lol_dba'

  gem 'rails_best_practices', require: false

  # Ruby/CLI: Automatic lossless reduction of all your images
  gem 'smusher'

  # Provides a breakdown of how much time is spent in 
  # each part of our app.
  gem 'rack-mini-profiler'
end


group :test do
  gem 'chronic'
end

group :development, :test do
  gem 'faker'
  
  gem 'rspec-rails', '~> 3.0.0.beta'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'guard-rspec', require: false

  gem 'pry-rails'
  gem 'pry-nav'
  gem 'pry-stack_explorer'

  # Turn off verbose logging of asset requests
  gem 'quiet_assets'

  # see Railscast for better_error gem
  # http://railscasts.com/episodes/402-better-errors-railspanel
  # FOR sublime text 3 MUST INSTALL sublime-url-protocol-mac, http://goo.gl/8KX1lb
  # http://goo.gl/8KX1lb
  gem 'better_errors'
  gem 'binding_of_caller'

  # Show a rails panel in Chrome. Requires a Chrome extension.
  # https://github.com/dejan/rails_panel
  gem 'meta_request'
end
