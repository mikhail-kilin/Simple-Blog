source "https://rubygems.org"

ruby "2.5.7"

gem "pg"
gem "rails", "5.2.4.2"

# assets
gem "autoprefixer-rails"
gem "coffee-rails"
gem "foundation-icons-sass-rails"
gem "foundation-rails", "~> 6.2.3.0"
gem "premailer-rails"
gem "sass-rails", "~> 5.0.0", ">= 5.0.6"
gem "uglifier", ">= 2.7.2"

# redactor
gem "carrierwave"
gem "ckeditor"
gem "mini_magick"

# amazon storage
gem "fog-aws"

source "https://rails-assets.org" do
  gem "rails-assets-jquery-ujs"
  gem "rails-assets-jquery2"
end

# views
gem "active_link_to"
gem "inky-rb", require: "inky"
gem "meta-tags"
gem "simple_form"
gem "slim"

# all other gems
gem "decent_decoration"
gem "decent_exposure"
gem "devise"
gem "draper"
gem "flamegraph"
gem "google-analytics-rails"
gem "health_check"
gem "interactor"
gem "kaminari"
gem "memory_profiler"
gem "puma"
gem "pundit"
gem "rack-canonical-host"
gem "rack-mini-profiler", require: false, git: "https://github.com/MiniProfiler/rack-mini-profiler.git"
gem "responders"
gem "rollbar"
gem "seedbank"
gem "stackprof"

group :staging, :production do
  gem "newrelic_rpm"
end

group :test do
  gem "capybara"
  gem "codeclimate-test-reporter", "0.6.0", require: false
  gem "database_cleaner"
  gem "email_spec"
  gem "formulaic"
  gem "guard-rspec"
  gem "launchy"
  gem "poltergeist"
  gem "rspec-its"
  gem "shoulda-matchers"
  gem "simplecov", "0.13.0", require: false
  gem "terminal-notifier-guard"
  gem "webmock", require: false
end

group :development, :test do
  gem "awesome_print"
  gem "brakeman", require: false
  gem "bullet"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "coffeelint"
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "faker"
  gem "jasmine", "2.5.2"
  gem "jasmine-core", "2.5.2"
  gem "jasmine-jquery-rails"
  gem "rspec-rails", "~> 3.5"
  gem "rubocop", "0.49.1", require: false
  gem "rubocop-rspec", require: false
  gem "scss_lint", require: false
  gem "slim_lint", "0.11.0", require: false
end

group :development do
  gem "letter_opener"
  gem "rails-erd"
  gem "slim-rails"
  gem "spring"
  gem "spring-commands-rspec"
  gem "spring-watcher-listen"
  gem "web-console"
end
