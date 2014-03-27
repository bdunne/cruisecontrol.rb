source "http://rubygems.org"

gem "rails", "3.2.16"
gem "rack", "~> 1.4.5"

gem "abstract", "1.0.0"
gem "api_cache", "0.2.0"
gem "bundler"
gem "columnize"
gem "debugger"
gem "debugger-linecache"
gem "debugger-ruby_core_source"
gem "httparty", "0.6.1"
gem "jquery-rails", '1.0.9'
gem "puma", '< 2.7.0'  # 2.7.[01] breaks compatibility with ruby 1.8.7
gem "rake", "~> 10.1.1"
gem "tzinfo"
gem "xml-simple", '1.0.16', :require => 'xmlsimple'
gem "xmpp4r"

group :development do
  gem "rcov", '0.9.9', :platforms => [:ruby_18]
  gem "mocha", :require => false #, "0.9.12", :require => false
  gem "rack-test", :require => "rack/test"
end

platform :jruby do
  gem 'jruby-openssl'
end

gem "googlecharts"

group :development do
  gem 'powder'
end

group :test do
  gem 'debugger', :platforms => :mri_19 unless ENV['TRAVIS'] == 'true'
end

gem 'system_timer', :platforms => :ruby_18
