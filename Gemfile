# A sample Gemfile
source "https://rubygems.org"

gem 'sinatra'
gem 'thin' #basic web server functionality
gem 'require_all'
gem 'activerecord', '5.2'
gem 'sinatra-activerecord'
gem 'rake'
	
	
group :development do # These gems won't be installed when the application is actually deployed, only for testing 
	gem 'shotgun'
	gem 'pry'
	gem 'tux' # interactive console that pre-loads our database and ActiveRecord relationships for us.
	gem 'sqlite3', '~> 1.3.6'
end 