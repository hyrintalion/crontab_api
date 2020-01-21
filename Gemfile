source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.2', '>= 6.0.2.1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

gem 'config' # Effortless multi-environment settings in Rails, Sinatra, Pandrino and others (https://github.com/railsconfig/config)
gem 'unicorn', '5.4.1' # Rack HTTP server for fast clients and Unix (https://bogomips.org/unicorn/)
gem 'json' # JSON Implementation for Ruby (http://flori.github.com/json)

# -- DRY & Patterns -- #
gem 'aasm' # State machine mixin for Ruby objects (https://github.com/aasm/aasm)
gem 'representable' # Renders and parses JSON/XML/YAML documents from and to Ruby objects. Includes plain properties, collections, nesting, coercion and more. (https://github.com/trailblazer/representable/)
gem 'draper' # View Models for Rails (http://github.com/drapergem/draper)
gem 'dry-validation' # A simple validation library (https://github.com/dry-rb/dry-validation)
gem 'dry-transaction' # Business Transaction Flow DSL (https://github.com/dry-rb/dry-transaction)
gem 'dry-container' # A simple container intended for use as an IoC container (https://github.com/dry-rb/dry-container)
gem 'dry-auto_inject' # Container-agnostic automatic constructor injection (https://github.com/dryrb/dry-auto_inject)


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-rails' # Use Pry as your rails console (https://github.com/rweng/pry-rails)

  gem 'factory_bot_rails' # factory_bot_rails provides integration between factory_bot and rails 4.2 or newer (https://github.com/thoughtbot/factory_bot_rails)
  gem 'rspec' # rspec-3.8.0 (http://github.com/rspec)
  gem 'shoulda-matchers', '~> 4.0' # Making tests easy on the fingers and eyes (https://matchers.shoulda.io/)
  gem 'rspec-rails' # RSpec for Rails (https://github.com/rspec/rspec-rails)
  gem 'rails-controller-testing' # Extracting `assigns` and `assert_template` from ActionDispatch. (https://github.com/rails/rails-controller-testing)
  gem 'ffaker' # Ffaker generates dummy data. (https://github.com/ffaker/ffaker)

  # -- Annotations -- #
  gem 'annotate' # Annotates Rails Models, routes, fixtures, and others based on the database schema. (http://github.com/ctran/annotate_models)
  gem 'annotate_gem' # Add comments to your Gemfile with each dependency's description. (https://github.com/ivantsepp/annotate_gem)
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
