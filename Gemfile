source 'https://rubygems.org'

# Bundling Edge @ 5.1.0.beta1 - TW 2017-03-05
gem 'rails', git: 'https://github.com/rails/rails.git'
gem 'pg'
gem 'puma'

# Assets & Core Libraries
gem 'sass-rails'
gem 'bootstrap-sass'
gem 'uglifier'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

# Development + Test Dependencies
group :development, :test do
  gem 'byebug', platform: :mri
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'rubocop', require: false
  gem 'capybara'
end

# Development-only Dependencies
group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
