source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

##Modified by vineet for heroku
# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
gem 'pg'
#gem 'taps'

gem 'rails_12factor', group: :production

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

#added by vineet
gem 'omniauth'
gem 'omniauth-twitter'
gem 'devise'
gem 'table_print'
gem 'hirb'
gem 'omniauth-facebook'

#vineet, for gapps
gem 'ruby-openid-apps-discovery'
#vineet for nifty:scaffold
gem "nifty-generators", :group => :development

#end vineet

#BEGIN VINEET - FOR PRODUCTION
# Add the following to the Gemfile
#gem 'capistrano'
#gem 'thin'
gem 'bigdecimal'

#picked up from http://www.talkingquickly.co.uk/2014/01/deploying-rails-apps-to-a-vps-with-capistrano-v3/
gem 'capistrano', '~> 3.1.0'

# rails specific capistrano funcitons
gem 'capistrano-rails', '~> 1.1.0'

# integrate bundler with capistrano
gem 'capistrano-bundler'

# if you are using RBENV
gem 'capistrano-rbenv', "~> 2.0" 

# Use the Unicorn app server
gem 'unicorn'
#end vineet

#Begin vineet
# to specify rails version on heroku
#ruby "2.1.1p76"
#end vineet

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
