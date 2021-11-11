source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'rails', '~> 6.0.4', '>= 6.0.4.1'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'bootsnap', '>= 1.4.2', require: false

group :development do
  gem 'listen', '~> 3.2'
  gem 'pry', '~> 0.13.1'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :development, :test do
  gem 'brakeman'
  gem 'bundler-audit'
  gem 'rspec-rails', '~> 5.0.0'
end

group :test do
  gem 'factory_bot_rails'
  gem 'shoulda-matchers', '~> 5.0'
end
