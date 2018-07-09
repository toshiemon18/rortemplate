source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.6'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jbuilder'
gem 'devise'
gem 'omniauth'
gem 'omniauth-facebook'
gem 'simple_form'

gem 'coffee-rails', '~> 4.2'
gem 'turbolinks'
gem 'jbuilder'

gem 'factory_bot_rails'
gem 'faker'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  gem "spring-commands-rspec"
  gem 'guard'
  gem 'terminal-notifier-guard'
  gem 'rspec-rails'
  gem 'database_rewinder'
  gem 'rspec-power_assert'
  gem 'rspec-parameterized'
  gem "rspec_junit_formatter"
  gem "shoulda-matchers", '2.8.0'
  gem 'timecop'
  gem 'webmock'
  gem 'rspec_junit_formatter'
  gem 'rspec-retry'
  gem 'rails-controller-testing'
  gem 'vcr'
  gem "shoulda-matchers", "2.8.0"
  gem 'slack-notifier'
  gem 'capybara-screenshot'
  gem 'fuubar'
  gem 'rubocop'
  gem 'rubocop-automata'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'spring-commands-rspec'
  gem 'view_source_map'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
