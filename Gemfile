source 'https://rubygems.org'

ruby '3.3.3'

##-- base gems for rails --##
gem 'rack-cors', '2.0.0', require: 'rack/cors'
gem 'rails', '~> 7.0.8.4'
gem 'bootsnap', require: false

##-- rails application helper gems --##
gem 'acts-as-taggable-on'
gem 'attr_extras'
gem 'browser'
gem 'hashie'
gem 'jbuilder'
gem 'kaminari'
gem 'responders', '>= 3.1.1'
gem 'rest-client'
gem 'telephone_number'
gem 'time_diff'
gem 'tzinfo-data'
gem 'valid_email2'
gem 'uglifier'
gem 'flag_shih_tzu'
gem 'haikunator'
gem 'liquid'
gem 'commonmarker'
gem 'json_schemer'
gem 'rack-attack', '>= 6.7.0'
gem 'down'
gem 'gmail_xoauth'
gem 'net-smtp',  '~> 0.3.4'
gem 'csv-safe'

##-- for active storage --##
gem 'aws-sdk-s3', require: false
gem 'azure-storage-blob', git: 'https://github.com/chatwoot/azure-storage-ruby', branch: 'chatwoot', require: false
gem 'google-cloud-storage', '>= 1.48.0', require: false
gem 'image_processing'

##-- gems for database --#
gem 'groupdate'
gem 'pg'
gem 'redis'
gem 'redis-namespace'
gem 'activerecord-import'

##--- gems for server & infra configuration ---##
gem 'dotenv-rails', '>= 3.0.0'
gem 'foreman'
gem 'puma'
gem 'vite_rails'
gem 'barnes'

##--- gems for authentication & authorization ---##
gem 'devise', '>= 4.9.4'
gem 'devise-secure_password', git: 'https://github.com/chatwoot/devise-secure_password', branch: 'chatwoot'
gem 'devise_token_auth', '>= 1.2.3'
gem 'jwt'
gem 'pundit'
gem 'administrate', '>= 0.20.1'
gem 'administrate-field-active_storage', '>= 1.0.3'
gem 'administrate-field-belongs_to_search', '>= 0.9.0'

##--- gems for pubsub service ---##
gem 'wisper', '2.0.0'

##--- gems for channels ---##
gem 'facebook-messenger'
gem 'line-bot-api'
gem 'twilio-ruby', '~> 5.66'
gem 'twitty', '~> 0.1.5'
gem 'koala'
gem 'slack-ruby-client', '~> 2.5.2'
gem 'google-cloud-dialogflow-v2', '>= 0.24.0'
gem 'grpc'
gem 'google-cloud-translate-v3', '>= 0.7.0'

##-- apm and error monitoring ---#
gem 'ddtrace', require: false
gem 'elastic-apm', require: false
gem 'newrelic_rpm', require: false
gem 'newrelic-sidekiq-metrics', '>= 1.6.2', require: false
gem 'scout_apm', require: false
gem 'sentry-rails', '>= 5.19.0', require: false
gem 'sentry-ruby', require: false
gem 'sentry-sidekiq', '>= 5.19.0', require: false

##-- background job processing --##
gem 'sidekiq', '>= 7.3.1'
gem 'sidekiq-cron', '>= 1.12.0'

##-- Push notification service --##
gem 'fcm'
gem 'web-push', '>= 3.0.1'

##-- geocoding / parse location from ip --##
gem 'geocoder'
gem 'maxminddb'

gem 'hairtrigger'
gem 'procore-sift'
gem 'email_reply_trimmer'
gem 'html2text'
gem 'working_hours'
gem 'pg_search'
gem 'stripe'

## - helper gems --##
gem 'faker'
gem 'lograge', '~> 0.14.0', require: false
gem 'omniauth-oauth2'
gem 'audited', '~> 5.4', '>= 5.4.1'
gem 'omniauth', '>= 2.1.2'
gem 'omniauth-google-oauth2', '>= 1.1.3'
gem 'omniauth-rails_csrf_protection', '~> 1.0', '>= 1.0.2'

## Gems for reponse bot
gem 'neighbor'
gem 'pgvector'
gem 'reverse_markdown'
gem 'iso-639'
gem 'ruby-openai'
gem 'shopify_api'

### Gems required only in specific deployment environments ###
gem 'annotate'

group :production do
  gem 'rack-timeout'
  gem 'judoscale-rails', require: false
  gem 'judoscale-sidekiq', require: false
end

group :development do
  gem 'bullet'
  gem 'letter_opener'
  gem 'scss_lint', require: false
  gem 'web-console', '>= 4.2.1'
  gem 'json_refs'
  gem 'squasher'
  gem 'rack-mini-profiler', '>= 3.2.0', require: false
  gem 'stackprof'
  gem 'meta_request', '>= 0.8.3'
end

group :test do
  gem 'database_cleaner'
  gem 'webmock'
  gem 'test-prof'
end

group :development, :test do
  gem 'active_record_query_trace'
  gem 'brakeman'
  gem 'bundle-audit', require: false
  gem 'byebug', platform: :mri
  gem 'climate_control'
  gem 'debug', '~> 1.8'
  gem 'factory_bot_rails', '>= 6.4.3'
  gem 'listen'
  gem 'mock_redis'
  gem 'pry-rails'
  gem 'rspec_junit_formatter'
  gem 'rspec-rails', '>= 6.1.5'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'seed_dump'
  gem 'shoulda-matchers'
  gem 'simplecov', '0.17.1', require: false
  gem 'spring'
  gem 'spring-watcher-listen'
end
