source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

# Auth library
gem "sorcery", "~> 0.16.4"

# Library for ruby html/css/js components
gem "view_component", "~> 2.80.0"

# Vite is Webpack but good
gem "vite_rails"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.4"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.4"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 6.2"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Use Redis adapter to run Action Cable in production
gem "redis", "~> 5.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "rspec-rails", "~> 6.0.1"
end

group :test do
  gem "factory_bot"
  gem "faker"
  gem "rails-controller-testing"
  gem "shoulda-matchers", "~> 5.2"
end

group :development do
  gem "better_errors"
  gem "guard"
  gem "guard-livereload"
  gem "letter_opener"
  gem "rack-livereload"
  gem "rubocop"
  gem "rubocop-performance"
  gem "rubocop-rails"
  gem "rubocop-rspec"
  gem "ruby-lsp", "~> 0.4.5"
  gem "web-console"
end
