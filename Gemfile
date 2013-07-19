source 'https://rubygems.org'

# Must specify Ruby version
ruby '2.0.0'

# Must include gem per https://devcenter.heroku.com/articles/rails-integration-gems
gem 'rails_12factor'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# Use sqlite3 as the database for Active Record
# Heroku does not like sqlite3 (sub pg), webrick (sub unicorn)
group :production do
  gem 'pg'
  gem 'unicorn'
end
group :development, :test do
  gem 'sqlite3'
  gem 'webrick'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end