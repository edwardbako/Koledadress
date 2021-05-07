source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'rails', '~> 6.0'

gem 'pg' # Use postgresql as the database for Active Record
gem 'puma' # Use Puma as the app server
gem 'kaminari'
# gem 'will_paginate' # Pagination library
# gem 'will_paginate-bootstrap' # Bootstrap styles for pagination links
gem 'sass-rails' # Use SCSS for stylesheets
gem 'slim-rails' # Slim markup for templates

gem 'webpacker' # Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks'
gem 'jbuilder' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'
gem 'russian' # I18n

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

gem 'spree', '~> 4.2'
gem 'spree_auth_devise', '~> 4.3'
gem 'spree_gateway', '~> 3.9'
gem 'spree_i18n', '~> 5.0'
gem 'spree_globalize', github: 'spree-contrib/spree_globalize'
# gem 'sassc', github: 'sass/sassc-ruby', branch: 'master' # only needed for MacOS and Ruby 3.0

gem 'redis'
gem 'hiredis'
gem 'redis-objects', github: "edwardbako/redis-objects", branch: "map_option" # Map Redis types directly to Ruby objects
gem 'sidekiq' # Queueing framework
gem 'sidekiq-cron' # Cron jobs for queueing
gem 'sinatra', :require => nil

gem 'devise' # Rack authentication

gem 'money-rails'

gem 'exception_notification'

gem 'pry-byebug' # Call 'binding.pry' anywhere in the code to stop execution and get a debugger console
gem 'pry-rails'
gem 'pry-doc'
gem 'pry-stack_explorer'
gem 'colorize' # Colorize strings output

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler'
  gem 'listen'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'letter_opener' # Open emails in browser

  gem 'capistrano'
  gem 'capistrano-rails'
  # gem 'capistrano-rvm'
  gem 'capistrano-rbenv'
  gem 'capistrano-bundler'
  gem 'capistrano-nodenv'
  gem 'capistrano-yarn'
  gem 'capistrano-sidekiq'
  gem 'capistrano3-puma', github: "seuros/capistrano-puma"
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
