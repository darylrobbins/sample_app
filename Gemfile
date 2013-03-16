source 'https://rubygems.org'

gem 'rails', '3.2.12'

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.13.0'
  gem 'guard-rspec', '2.5.1'
  gem 'guard-spork', '1.5.0'
  gem 'spork', '0.9.2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.2'

group :test do
  gem 'capybara', '2.0.2'
  gem 'rb-fsevent', '0.9.3', :require => false if RUBY_PLATFORM =~ /darwin/i
end

group :production do
  gem 'pg', '0.12.2'
end
