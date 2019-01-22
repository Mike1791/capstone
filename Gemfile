source 'https://rubygems.org'

gem 'rails', '4.2.6'
gem 'rails-api'
# gem 'pry-rails', '~>0.3.4'
gem 'jbuilder', '~>2.0'
gem 'spring', :group => :development
gem 'pg', '~>0.15'
gem 'mongoid', '~>5.1.5'
gem 'mongo', '~>2.4.0'
gem 'rack-cors', '~>0.4.0', :require => 'rack/cors'

group :development, :test do
  gem 'webrick', '~>1.3.1', :platforms=>[:mingw, :mswin, :x64_mingw, :jruby]
  # gem 'tzinfo-data', :platforms=>[:mingw, :mswin, :x64_mingw, :jruby]
  # gem 'sqlite3', '~>1.3.12'
  gem 'byebug', '~>9.0.6'
  # gem 'pry-byebug', '~>3.4.0'
  gem 'httparty', '~>0.14.0'

  gem 'rspec-rails', '~> 3.5.2'
  # gem 'mongoid-rspec', '~> 3.0.0'
  # gem 'capybara', '~> 2.10.1'
  # gem 'poltergeist', '~> 1.11.0'
  # gem 'selenium-webdriver', '~> 2.53.4'
  # gem 'chromedriver-helper', '~>1.0.0'
  # gem 'launchy', '~>2.4.3'
  # gem 'simplecov', '~>0.12', :require=>false
end

group :production do
  gem 'rails_12factor', '~>0.0.3'
  gem 'puma', '~>3.6.0', :platforms=>:ruby
end
