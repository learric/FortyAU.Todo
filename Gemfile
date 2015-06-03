source 'https://rubygems.org'

gem 'rails', '4.2.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'faker'

gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'bower-rails'
gem 'angular-rails-templates'

gem "foreman"

group :production, :staging do
	gem "pg"
	gem "rails_12factor"
	gem "rails_stdout_logging"
	gem "rails_serve_static_assets"
end

group :development, :test do
	gem 'sqlite3'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]