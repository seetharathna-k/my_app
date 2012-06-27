source 'https://rubygems.org'

gem 'rails', '3.2.6'

group :development do
  gem 'rspec-rails' 
  gem 'sqlite3', '1.3.5'
end

#gem "rspec-rails", ">= 2.8.0.rc1", :group => [:development, #test]

group :test do
  gem "rspec-rails"
  gem "factory_girl_rails", ">= 1.3.0" 
  gem "cucumber-rails", ">= 1.1.1"
  gem "capybara", ">= 1.1.1" 
  gem "database_cleaner", ">= 0.6.7" 
  gem 'simplecov', :require => false
  gem "launchy", ">= 2.0.5" 
  # Pretty printed test output
  gem 'turn', '< 0.8.3', :require => false
end


gem 'mysql'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.3'
  gem 'coffee-rails', '3.2.1'

  gem 'uglifier', '1.0.3'
end

gem 'jquery-rails', '2.0.0'

group :production do
  gem 'pg'
end

