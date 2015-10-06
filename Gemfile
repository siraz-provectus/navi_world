source 'https://rubygems.org'
ruby '2.2.2'

gem 'rails', '4.2.4'
gem 'pg', '~> 0.17'

# Assets
gem 'bootstrap-sass', '~> 3.1.1'
gem 'slim-rails', '~> 3.0.1'
gem 'html2slim', '~> 0.1.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'

# Main stuff
gem 'devise', '~> 3.4'
gem 'active_hash'
gem "state_machine"

# Uploads
gem 'carrierwave'
gem 'fog'
gem "fog-aws"
gem "mini_magick"

# Background jobs
gem 'sidekiq'
gem 'sidekiq-status'
gem 'sinatra', require: false
gem 'redis-rails'

# Deployment and Server related gems
gem 'foreman'
gem 'unicorn'
gem 'whenever', require: false
gem "dotenv-rails"

# Decorators & Exposing named methods
gem 'decent_exposure'

# Localization
gem "russian"

# Permissions
gem 'pundit'

# Search
gem 'searchlight'

gem 'geocoder'
#gem 'rest-client'

gem 'jbuilder'

group :test do
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'rspec-rails'
  gem 'shoulda-matchers', require: false
  gem 'rspec-sidekiq'
end

group :development do
  gem "rails-erd"
  gem "brakeman", require: false
  gem 'capistrano', '~> 3.2.0'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano-rbenv'
  gem 'capistrano-sidekiq'
  gem "pry-rails"
  gem 'letter_opener'
  gem 'quiet_assets'
  gem 'annotate', git: 'git://github.com/ctran/annotate_models.git'
  gem 'better_errors'
end

group :test, :development do
  gem 'factory_girl_rails'
  gem 'byebug'
end


