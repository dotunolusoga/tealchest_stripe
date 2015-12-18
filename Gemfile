ruby '2.2.3'
#ruby-gemset=tealchest_stripe
source 'https://rubygems.org'


# Authorization gem:  gives us Ability model and can? :edit, item
gem 'cancan'
# Coffeescript
gem 'coffee-rails', '~> 4.1.0'
#simple helper to get an HTML select list of countries
gem 'country_select'
# Magic Sauce.  We will get to this.
gem 'decent_exposure'
# Authentication
gem 'devise'
# Object factories
gem 'fabrication'
# Stores environment variables
gem 'figaro'
# Stores files in the cloud
gem 'fog'
# Enables HAML views
gem 'haml-rails'
# Error reporting
gem 'honeybadger'
# jquery on rails:
gem 'jquery-rails'
# jquery-ui on rails:
gem 'jquery-ui-rails'
#lightweight grid framework for Sass & Bourbon
gem 'neat'
# Postgres gem
gem 'pg'
# rails server that handles multiple connections
gem 'puma'
gem 'rails', '4.2.1'
# Sassy
gem 'sass-rails'
# Improves on Rails form_for:
gem 'simple_form'
# Compresses javacript and css:
gem 'uglifier', '>= 1.3.0'



group :production do
  # Makes the heroku logs more informative:
  gem 'rails_12factor'
end

group :development do
  # Creates viewable ERD
  gem 'rails-erd'
end

group :test, :development do
  # Generates reasonable looking fake data
  gem 'faker'
  # For debugging:
  gem 'pry-rails'
  # Testing:
  gem 'rspec-rails', '~> 3.0'
  gem 'rspec', '~> 3.0'
  gem 'spring'
end

group :test do
  gem 'capybara'
  # Sends code coverage information to code climate
  gem 'codeclimate-test-reporter', require: false
  # Cleans up our test database
  gem 'database_cleaner'
  # Enables save_and_open_page from Capybara
  gem 'launchy'
  # Helpers for testing AR, etc.
  gem 'shoulda-matchers'
  # Mocks external requests and allows you to disable external request
  gem 'webmock'
  # Records external requests
  gem 'vcr'
end
