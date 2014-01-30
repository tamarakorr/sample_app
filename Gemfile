source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.2'
gem 'bootstrap-sass', '2.3.2.0'
gem 'pg', '0.15.1'

group :development, :test do
  gem 'rspec-rails', '2.13.1'
  gem 'guard-rspec', '2.5.0'
  
  # Spork
  gem 'spork-rails', '4.0.0'
  #gem 'guard-spork', '1.5.0' #Known problem with spork+guard
  gem 'guard-spork', :github => 'guard/guard-spork' #resolution from StackOverflow
  gem 'childprocess', '0.3.6'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
end

  # Uncomment this line on OS X.
  # gem 'growl', '1.0.3'

  # Uncomment these lines on Linux.
  # gem 'libnotify', '0.8.0'

# Uncomment these lines on Windows.
gem 'rb-notifu', '0.0.4'
#gem 'win32console', '1.3.2' ...but apparently not this one

# tko heroku problem documented at
# http://stackoverflow.com/questions/15786942/error-when-running-heroku-run-rake-dbmigrate-3
#WINDOWS Gems That don't play well with nix
platforms :mswin do 
  gem 'wdm', '0.1.0'
end
  
gem 'sass-rails', '4.0.1'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  #gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end