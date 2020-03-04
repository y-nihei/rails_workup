source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '5.1.6'
gem 'puma', '3.12.4'
gem 'sass-rails', '5.0.6'
gem 'uglifier', '3.2.0'
gem 'coffee-rails', '4.2.2'
gem 'turbolinks', '5.0.1'
gem 'jbuilder', '2.6.4'
gem 'jquery-rails', '4.3.1'

group :development, :test do
  gem 'sqlite3', '1.3.13'
  gem 'byebug', '9.0.6', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
