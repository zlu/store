source 'https://rubygems.org'

gem 'rails', '3.2.7'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# To use debugger
# gem 'debugger'

gem 'spree', '1.1.3'
gem 'spree_usa_epay'
gem 'spree_skrill'
gem 'spree_gateway', :git => 'git://github.com/spree/spree_gateway.git', :branch => "1-1-stable" # make sure to include after spree

group :production do
  gem 'unicorn'
  gem 'mysql2'
  gem 'foreman'
  gem 'therubyracer' #only required for 0.70.x or later
end
 
group :development do
  gem 'capistrano'
end

group :development, :test do
  gem 'sqlite3'
end