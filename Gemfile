source 'https://rubygems.org'

#NP ruby-2.0.0-p353
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# Use sqlite3 as the database for Active Record
# gem 'sqlite3'
#NP development environment
#Note that we’ve also taken this opportunity to arrange for the gem 
#to be included only in a   development environment   (Section 7.1.1), 
#which prevents potential conflicts with the database used by Heroku (Section 1.4).
group :development do
  gem 'sqlite3', '1.3.8'
end

# Use SCSS for stylesheets
# gem 'sass-rails', '~> 4.0.0'
#NP
gem 'sass-rails',   '4.0.1'

# Use Uglifier as compressor for JavaScript assets
# gem 'uglifier', '>= 1.3.0'
#NP
gem 'uglifier', '2.1.1'

# Use CoffeeScript for .js.coffee assets and views
# gem 'coffee-rails', '~> 4.0.0'
#NP
gem 'coffee-rails', '4.0.1'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
# gem 'jquery-rails'
#NP
gem 'jquery-rails', '3.0.4'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

#NP 1.4.1 Heroku setup
#add the pg gem in the production environment to allow Rails to talk to Postgres
#rails_12factor gem, is used by Heroku to serve static assets such as images and stylesheets.
group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
