source 'https://rubygems.org'
ruby '2.0.0'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.1'

# Use postgresql as the database for Active Record
gem 'pg'

group :production do
  gem 'unicorn'
  gem 'foreman'
  gem 'pg'
  gem 'therubyracer'
end

group :development do
  gem 'capistrano'
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
gem 'rails_12factor', group: :production

gem 'spree', '2.1.3'
gem 'spree_gateway', :git => 'https://github.com/spree/spree_gateway.git', :branch => '2-1-stable'
gem 'spree_auth_devise', :git => 'https://github.com/spree/spree_auth_devise.git', :branch => '2-1-stable'
gem 'spree_fancy', :github => 'spree/spree_fancy', :branch => '2-1-stable'
gem "spree_address_book", :git => "https://github.com/bloomcrush/spree_address_book.git", :branch => '2-1-stable'
gem "spree_product_zoom", :git => "git://github.com/tuxdapenguin/spree_product_zoom.git", :branch => "2-1-stable"
gem 'spree_variant_options', :git => 'git://github.com/tuxdapenguin/spree_variant_options.git', :branch => "2-1-stable"
gem 'spree_conekta', git: 'git://github.com/crowdint/spree_conekta.git'
gem 'spree_i18n', github: 'spree/spree_i18n', branch: '2-1-stable'
