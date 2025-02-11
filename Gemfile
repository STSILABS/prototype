source 'https://rubygems.org'

ruby '2.1.5'

gem 'rails', '4.2.0'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# HTTParty to interact with external REST APIs
gem 'httparty'
# Be able to read/write MS Excel (.xlsx) files
gem 'rubyXL'

# Use jquery as the JavaScript library  
# gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'
gem 'sass', '3.2.19' 
gem 'bower-rails'
gem 'angular-rails-templates'

# gem 'puma'
gem "foreman"
group :production, :staging do
  gem "rails_12factor"
  gem "rails_stdout_logging"
  gem "rails_serve_static_assets"
end

group :development do 
  gem "better_errors"
  gem "binding_of_caller"
end

group :test, :development do
  gem 'rspec-rails', '~> 3.0.0'
  gem 'cucumber-rails', :require => false
  # gem "factory_girl_rails", "~> 4.0"
  gem "capybara"
  gem "database_cleaner"
  gem "selenium-webdriver"
  gem "teaspoon"
  gem "poltergeist"
  gem "phantomjs"
  gem 'dotenv-rails'

end

# Windows
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

