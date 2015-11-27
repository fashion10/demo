source 'https://rubygems.org'
ruby '2.1.2'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4' #railsのバージョンは、tutorial通りにさげた。元は、4.2.4
gem 'sprockets'
gem 'autoprefixer-rails'
gem 'bcrypt-ruby'
gem 'bootstrap-sass', '~> 2.3.2.0'
gem 'faker'
gem 'ffaker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'

# Use mysql as the database for Active Record
gem 'mysql2', '0.3.20'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby
# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery-ui-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '1.1.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

gem 'shoulda-matchers'

#gem "minitest"
# bundle exec rake doc:rails generates the API under doc/api.
group :doc do
  gem 'sdoc', '~> 0.4.0', require: false
end
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'
# Use Unicorn as the app server
# gem 'unicorn'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

group :development, :test do
  #gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.14.0.rc1'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'hirb'
  gem 'hirb-unicode'
  gem 'spring'
  gem "minitest"
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'factory_girl_rails'
end

group :development do
  gem 'web-console', '~> 2.0'
end
