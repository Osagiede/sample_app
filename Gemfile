source 'https://rubygems.org'

ruby '2.5.1'

gem 'rails', '5.2.0'
gem 'puma', '3.11.4'
gem 'sass-rails', '5.0.7'
gem 'uglifier', '4.1.10'
gem 'coffee-rails', '4.2.2'
gem 'jquery-rails', '4.3.3'
gem 'turbolinks', '5.1.1'
gem 'jbuilder', '2.7.0'
# gem 'bootsnap', '1.3.0' # Added to fix the bootsnap/setup heroku error 

group :development, :test do
  gem 'sqlite3', '1.3.13'
  gem 'byebug', '10.0.2', platform: :mri
end

group :development do
  gem 'web-console', '3.6.2'
  gem 'listen', '3.1.5'
  gem 'spring', '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'rails-controller-testing', '1.0.2'
  gem 'minitest', '5.11.3'
  gem 'minitest-reporters', '1.2.0'
  gem 'guard', '2.14.2'
  gem 'guard-minitest', '2.4.6'
end

group :production do
  gem 'pg', '1.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
