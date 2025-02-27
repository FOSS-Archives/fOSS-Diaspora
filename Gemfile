# frozen_string_literal: true

source "https://rubygems.org"

gem "rails", "5.2.7.1"

# Legacy Rails features, remove me!
# responders (class level)
gem "responders", "3.0.1"

# Appserver

gem "unicorn", "6.0.0", require: false
gem "unicorn-worker-killer", "0.4.5"

# Federation

gem "diaspora_federation-json_schema", "0.2.7"
gem "diaspora_federation-rails", "0.2.7"

# API and JSON

gem "acts_as_api", "1.0.1"
gem "json",        "2.3.0"
gem "json-schema", "2.8.1"
gem "yajl-ruby",   "1.4.2"

# Authentication

gem "devise", "4.8.0"
gem "devise_lastseenable", "0.0.6"
gem "devise-two-factor", "4.0.2"
gem "rqrcode", "2.1.0"

# Captcha

gem "simple_captcha2", "0.5.0", require: "simple_captcha"

# Background processing

gem "redis", "4.5.1"
gem "sidekiq", "6.4.0"

# Scheduled processing

gem "sidekiq-cron", "1.2.0"

# Compression

gem "terser", "1.1.7"

# Configuration

gem "configurate", "0.5.0"
gem "toml-rb", "2.1.0"

# Cross-origin resource sharing

gem "rack-cors", "1.1.1", require: "rack/cors"

# CSS

gem "autoprefixer-rails",     "10.3.3.0"
gem "bootstrap-sass",         "3.4.1"
gem "bootstrap-switch-rails", "3.3.3" # 3.3.4 and 3.3.5 is broken, see https://github.com/Bttstrp/bootstrap-switch/issues/691
gem "compass-rails",          "3.1.0"
gem "sass-rails",             "5.0.7"
gem "sprockets-rails",        "3.2.2"

# Database

group :mysql, optional: true do
  gem "mysql2", "0.5.3"
end
group :postgresql, optional: true do
  gem "pg",     "1.2.3"
end

gem "activerecord-import", "1.1.0"

# File uploading

gem "carrierwave", "2.2.2"
gem "fog-aws",     "3.12.0"
gem "mini_magick", "4.11.0"

# GUID generation
gem "uuid", "2.3.9"

# Icons

gem "entypo-rails", "3.0.0"

# JavaScript

gem "handlebars_assets", "0.23.9"
gem "jquery-rails",      "4.4.0"
gem "jquery-ui-rails",   "5.0.5"
gem "js-routes",         "2.1.2"
gem "js_image_paths",    "0.1.1"
gem "sprockets-es6",     "0.9.2"

source "https://gems.diasporafoundation.org" do
  gem "rails-assets-jquery",                              "3.5.1" # Should be kept in sync with jquery-rails

  gem "rails-assets-highlightjs",                         "9.12.0"
  gem "rails-assets-markdown-it",                         "8.4.2"
  gem "rails-assets-markdown-it-diaspora-mention",        "1.2.0"
  gem "rails-assets-markdown-it-footnote",                "3.0.3"
  gem "rails-assets-markdown-it-hashtag",                 "0.4.0"
  gem "rails-assets-markdown-it--markdown-it-for-inline", "0.1.1"
  gem "rails-assets-markdown-it-sanitizer",               "0.4.3"
  gem "rails-assets-markdown-it-sub",                     "1.0.0"
  gem "rails-assets-markdown-it-sup",                     "1.0.0"

  gem "rails-assets-backbone",                            "1.3.3"
  gem "rails-assets-bootstrap-markdown",                  "2.10.0"
  gem "rails-assets-corejs-typeahead",                    "1.2.1"
  gem "rails-assets-cropperjs",                           "1.4.3"
  gem "rails-assets-fine-uploader",                       "5.13.0"
  gem "rails-assets-pica",                                "5.0.0"

  # jQuery plugins

  gem "rails-assets-autosize",                            "4.0.2"
  gem "rails-assets-blueimp-gallery",                     "2.33.0"
  gem "rails-assets-jquery.are-you-sure",                 "1.9.0"
  gem "rails-assets-jquery-placeholder",                  "2.3.1"
  gem "rails-assets-jquery-textchange",                   "0.2.3"
  gem "rails-assets-utatti-perfect-scrollbar",            "1.4.0"
end

gem "markdown-it-html5-embed", "1.0.0"

# Localization

gem "http_accept_language", "2.1.1"
gem "i18n-inflector-rails", "1.0.7"
gem "rails-i18n",           "5.1.3"

# Mail

gem "markerb",             "1.1.0"

# Map
gem "leaflet-rails",       "1.7.0"

# Parsing

gem "nokogiri",          "1.13.4"
gem "open_graph_reader", "0.7.2" # also update User-Agent in features/support/webmock.rb and open_graph_cache_spec.rb
gem "redcarpet",         "3.5.1"
gem "ruby-oembed",       "0.15.0"
gem "twitter-text",      "3.1.0"

# RTL support

gem "string-direction", "1.2.2"

# Security Headers

gem "secure_headers", "6.3.3"

# Services

gem "omniauth",                       "2.0.4"
gem "omniauth-rails_csrf_protection", "1.0.0"
gem "omniauth-tumblr",                "1.2"
gem "omniauth-twitter",               "1.4.0"
gem "omniauth-wordpress",             "0.2.2"
gem "twitter",                        "7.0.0"

# OpenID Connect
gem "openid_connect", "1.3.0"

# Serializers

gem "active_model_serializers", "0.9.7"

# Tags

gem "acts-as-taggable-on", "8.1.0"

# URIs and HTTP

gem "addressable",        "2.8.0", require: "addressable/uri"
gem "faraday",            "0.17.4"
gem "faraday-cookie_jar", "0.0.7"
gem "faraday_middleware", "0.14.0"
gem "typhoeus",           "1.4.0"

# Views

gem "gon",                     "6.4.0"
gem "hamlit",                  "2.15.1"
gem "mobile-fu",               "1.4.0"
gem "rails-timeago",           "2.19.1"
gem "will_paginate",           "3.3.1"

# Logging

gem "logging-rails", "0.6.0", require: "logging/rails"

# Reading and writing zip files

gem "rubyzip", "2.3.2", require: "zip"

# Prevent occasions where minitest is not bundled in
# packaged versions of ruby. See following issues/prs:
# https://github.com/gitlabhq/gitlabhq/issues/3826
# https://github.com/gitlabhq/gitlabhq/pull/3852
# https://github.com/discourse/discourse/pull/238
gem "minitest"

gem "versionist", "2.0.1"

# Windows and OSX have an execjs compatible runtime built-in, Linux users should
# install Node.js or use "therubyracer".
#
# See https://github.com/sstephenson/execjs#readme for more supported runtimes

# gem "therubyracer", :platform => :ruby

group :production do # we don"t install these on travis to speed up test runs
  # Analytics

  gem "rack-google-analytics", "1.2.0"
  gem "rack-piwik",            "0.3.0",  require: "rack/piwik"

  # Process management

  gem "eye", "0.10.0"

  # Redirects

  gem "rack-rewrite", "1.5.1", require: false
  gem "rack-ssl",     "1.4.1", require: "rack/ssl"

  # Third party asset hosting

  gem "asset_sync", "2.15.0", require: false
end

group :development do
  # Linters
  gem "haml_lint",      "0.37.1", require: false
  gem "pronto",         "0.11.0", require: false
  gem "pronto-eslint",  "0.11.0", require: false
  gem "pronto-haml",    "0.11.0", require: false
  gem "pronto-rubocop", "0.11.1", require: false
  gem "pronto-scss",    "0.11.0", require: false
  gem "rubocop",        "0.93.1", require: false
  gem "rubocop-rails",  "2.9.1", require: false

  # Debugging
  gem "pry"
  gem "pry-byebug"

  # test coverage
  gem "simplecov", "0.21.2", require: false

  gem "turbo_dev_assets", "0.0.2"

  gem "listen", "3.5.1"
end

group :test do
  # RSpec (unit tests, some integration tests)

  gem "fixture_builder",   "0.5.2"
  gem "fuubar",            "2.5.1"
  gem "json-schema-rspec", "0.0.4"
  gem "rspec-json_expectations", "~> 2.1"

  # Cucumber (integration tests)

  gem "apparition",       "0.6.0"
  gem "capybara",         "3.35.3"
  gem "database_cleaner-active_record", "2.0.1"

  gem "cucumber-api-steps", "0.14", require: false

  # General helpers

  gem "factory_bot_rails", "6.1.0"
  gem "shoulda-matchers",  "4.5.1"
  gem "timecop",           "0.9.4"
  gem "webmock",           "3.14.0", require: false

  gem "diaspora_federation-test", "0.2.7"
end

group :development, :test do
  # RSpec (unit tests, some integration tests)
  gem "rspec-rails", "5.0.2"

  # Cucumber (integration tests)
  gem "cucumber-rails", "2.4.0", require: false

  # Jasmine (client side application tests (JS))
  gem "chrome_remote",             "0.3.0"
  gem "jasmine",                   "3.10.0"
  gem "jasmine-jquery-rails",      "2.0.3"
  gem "rails-assets-jasmine-ajax", "4.0.0", source: "https://gems.diasporafoundation.org"
  gem "sinon-rails",               "1.15.0"

  # For `assigns` in controller specs
  gem "rails-controller-testing", "1.0.5"
end
