source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby "2.4.1"

# Rails engine for https://github.com/CodeSeven/toastr
gem 'toastr-rails'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.2'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# ActiveModel validation for email. Including MX lookup and disposable email blacklist
gem "valid_email2"
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
# Ckeditor integration gem for rails http://ckeditor.com/
gem 'ckeditor'
# A Ruby gem for on-the-fly processing - suitable for image uploading in Rails, Sinatra and much more!
gem 'dragonfly'
# Minimal authorization through OO design and pure Ruby classes
gem "pundit"
# Flexible authentication solution for Rails with Warden.
gem 'devise'
# Translations for the devise gem
gem 'devise-i18n'
# A library to handle IP (both IPv4 and IPv6) addresses in a modern and productive way.
gem 'ipaddress'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Repository for collecting Locale data for Ruby on Rails I18n
gem 'rails-i18n'
# the font-awesome font bundled as an asset for the rails asset pipeline
gem 'font-awesome-rails'

source 'https://rails-assets.org' do
  # The most popular front-end framework for developing responsive, mobile first projects on the web.
  gem 'rails-assets-bootstrap'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
end

group :production do
  gem 'pg'
end

group :development do
  gem 'mailcatcher'
  # Better error page for Rack apps
  gem 'better_errors'
  # Rails >= 3 pry initializer
  gem 'pry-rails'
  # O Lero-lero Generator é uma ferramenta capaz de gerar frases que 'falam' muita coisa mas que não tem conteúdo algum.
  gem 'lerolero_generator'
  # A library for generating fake data such as names, addresses, and phone numbers.
  gem 'faker'
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
