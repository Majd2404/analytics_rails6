# README

# **Ahoy** 
# Track visits and events in Ruby, JavaScript, and native apps. Data is stored in your database by default so you can easily combine it with other data.
# One of the many benefits of Rails is its rich ecosystem of open source gems which can provide massive value quickly. We discovered one such gem, Ahoy,

+ Add this line to your application’s Gemfile:

  gem 'ahoy_matey'

+ bundle install
+ rails generate ahoy:install
+ rails db:create
+ rails db:migrate

# JavaScript, Native Apps, & AMP
# Enable the API in config/initializers/ahoy.rb:
  Ahoy.api = true
# Download ahoy.js and include it on your page.
# <script src="ahoy.js"></script>
# Or use Yarn:
  yarn add ahoy.js
 
# And add to app/javascript/packs/application.js:
  import ahoy from "ahoy.js";  