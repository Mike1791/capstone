source 'https://rubygems.org'

ruby '2.4.5'
gem 'rails', '4.2.8'
gem 'rails-api'
# gem 'pry-rails', '~>0.3.4'
gem 'spring', :group => :development
gem 'pg', '~>0.15'
gem 'mongoid', '~>5.1.5'
gem 'mongo', '~>2.4.0'
gem 'rack-cors', '~>0.4.0', :require => 'rack/cors'

gem 'sass-rails', '~> 5.0.6'
gem 'uglifier', '~> 3.0.2'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails', '~>4.2.1'
gem 'jbuilder', '~> 2.6.0'

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
  gem 'puma', '~>3.7.0', :platforms=>:ruby
end

source 'https://rails-assets.org' do
  gem 'rails-assets-bootstrap', '~>3.3.7'
  gem 'rails-assets-angular', '~>1.5.9'
  gem 'rails-assets-angular-ui-router', '~>0.3.1'
  gem 'rails-assets-angular-resource', '~>1.5.9'
end