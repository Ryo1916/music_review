source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# base
gem 'rails',      '5.2.3'
gem 'pg',         '1.1.4'
gem 'puma',       '3.12.1'
gem 'bootsnap',   '>= 1.1.0', require: false
gem 'jbuilder',   '2.9.1'
gem 'uglifier',   '4.1.20'
gem 'turbolinks', '5.2.0'

# css
gem 'bootstrap',         '4.3.1'
gem 'font-awesome-sass', '5.6.1'
gem 'sassc-rails',       '2.1.2'

# js
gem 'jquery-rails', '4.3.5'
gem 'popper_js',    '1.14.5'

# file upload
gem 'mini_magick', '4.9.2'

# i18n
gem 'http_accept_language', '2.1.1'
gem 'i18n',                 '1.6.0'
gem 'i18n-tasks',           '0.9.25'
gem 'rails-i18n',           '5.1.1'

# account
gem 'devise', '4.7.1'

# seo
gem 'meta-tags',         '2.11.1'
gem 'sitemap_generator', '6.0.2'

# surveillance
gem 'rollbar', '2.20.2'

# others
gem 'faker',     '1.9.4'
gem 'rails-erd', '1.5.2'

group :development, :test do
  gem 'annotate',                 '2.7.5'
  gem 'byebug',                   '10.0', platform: :mri
  gem 'capybara',                 '~> 2.13'
  gem 'chromedriver-helper',      '2.1.0'
  gem 'database_cleaner',         '1.7.0'
  gem 'factory_bot_rails',        '4.11.1'
  gem 'guard',                    '2.13.0'
  gem 'pry-byebug',               '3.6.0'
  gem 'pry-doc',                  '1.0.0'
  gem 'pry-rails',                '0.3.9'
  gem 'rails-controller-testing', '1.0.4'
  gem 'rspec-rails',              '3.8.1'
  gem 'selenium-webdriver',       '3.141.0'
  gem 'shoulda-matchers',         '3.1.2'
  gem 'simplecov',                '0.16.1'
  gem 'test-queue',               '0.4.2'
end

group :development do
  gem 'better_errors',         '2.5.0'
  gem 'binding_of_caller',     '0.8.0'
  gem 'letter_opener_web',     '1.3.4'
  gem 'listen',                '3.1.5'
  gem 'overcommit',            '0.46.0'
  gem 'rubocop',               '0.72.0'
  gem 'spring',                '2.0.2'
  gem 'spring-commands-rspec', '1.0.4'
  gem 'spring-watcher-listen', '2.0.1'
  gem 'web-console',           '3.5.1'
end

group :production do
  gem 'aws-sdk-s3', '1.44.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
