source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.0'

# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'

# Use Puma as the app server
gem 'puma', '~> 3.7'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'

# Jquery for rails
gem 'jquery-rails'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5.0'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use resque for jobs.  Email, account creation, other stuff
# gem 'resque'
# Use ActiveModel has_secure_password

# Bcrypt for passwords
gem 'bcrypt-ruby', '~> 3.0.0', :require => "bcrypt"

# Use devise for authentication and user roles
gem 'devise'

# Use CanCan for managing users via Admin role
gem 'cancancan', '~> 2.0'

# Bootstrap 4
gem 'bootstrap', '~> 4.0.0.beta'

# Required in production
# @see https://stackoverflow.com/questions/38663706/loaderror-could-not-load-the-listen-gem-rails-5
gem 'listen', '>= 3.0.5', '< 3.2'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # pry + byebug
  gem 'pry-byebug'
  gem 'pry-awesome_print'

  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'

  # For test data creation
  gem 'faker', '~> 1.8', '>= 1.8.4'

  # Use Rspec for testing
  gem 'rspec-rails', '>= 3.5'

  # Windows Directory Monitor
  gem 'wdm', '>= 0.1.0' if Gem.win_platform?

  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
