# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

File.read('./.ruby-version')

gem 'dotenv-rails', groups: %i[development test]

gem 'bootsnap', '>= 1.1.0', require: false
gem 'coffee-rails', '~> 4.2'
gem 'devise', '~> 4.7.1'
gem 'faker', '~> 1.8', '>= 1.8.7'
gem 'feathericon-sass'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.4'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
gem 'mailjet'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.1', '>= 5.2.1.1'
gem 'sass-rails', '~> 5.0'
gem 'sidekiq', '~> 5.2.2'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails', '~> 4.0'
  gem 'rspec-rails', '~> 3.7', '>= 3.7.2'
  gem 'sandi_meter', '~> 1.2'
end

group :development do
  gem 'annotate', '~> 2.7', '>= 2.7.4'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop', require: false
  gem 'rubocop-rspec', require: false
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'database_cleaner', '~> 1.7'
  gem 'rspec_in_context'
  gem 'rspec_junit_formatter'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'simplecov', '~> 0.16.1', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
