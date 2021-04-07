source "http://rubygems.org"

gem "sinatra"
gem "activerecord", "~> 5.2", :require => "active_record"
gem "sinatra-activerecord", :require => "sinatra/activerecord"
gem "rake"
gem "require_all"
gem "thin"
gem "shotgun"
gem "pry"
gem "bcrypt"
gem "sinatra-flash"

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :test do
  gem "rspec"
  gem "capybara"
  gem "rack-test"
end
