source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.10'


gem 'rails', '~> 5.2.5'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false

# For SignIn with email
gem 'clearance'

# Added for Solargraph
gem 'nokogiri', '~>1.10.10'

# file attachment library for ActiveRecord
# Should switch to Rails' ActiveStorage
gem 'paperclip'

# For using Solr
gem 'sunspot_rails'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'ruby-debug-ide' 
  gem 'debase' 
  gem 'solargraph' 
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
