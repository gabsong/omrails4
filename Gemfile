source 'https://rubygems.org'

# Set ruby version
ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use PostgreSQL as the database for Heroku
# Heroku: Add 'rails_12factor' gem to skip plugin injection
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# Use sqlite3 as the database for Active Record
group :development, :test do
  gem 'sqlite3'
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
gem 'jquery-turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# Bootstrap for Sass - Bootstrap 3
gem 'bootstrap-sass', github: 'thomas-mcdonald/bootstrap-sass', branch: '3'

# Use Devise for user authentication
gem 'devise', '~> 3.1.1'

# Use Paperclip for file attachment management
gem 'paperclip', '~> 3.0'

# Use Amazon AWS for Paperclip file storage
gem 'aws-sdk', '~> 1.23.0'

# Masonry-Rails for arranging item elements to a grid
gem 'masonry-rails', '~> 0.2.0'

# Pagination library for Rails
gem 'will_paginate', '~> 3.0'
gem 'will_paginate-bootstrap'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
