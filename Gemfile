source "https://rubygems.org"

# Rails framework (use latest stable 7.2.x)
gem "rails", "~> 8.0.3"

# Original Rails asset pipeline
gem "sprockets-rails"

# PostgreSQL adapter for Active Record
gem "pg", "~> 1.1"

# Puma web server
gem "puma", ">= 5.0"

# Use JavaScript with ESM import maps
gem "importmap-rails"

# Hotwire Turbo for SPA-like page updates
gem "turbo-rails"

# Hotwire Stimulus for modest JavaScript framework
gem "stimulus-rails"

# JSON builder for APIs
gem "jbuilder"

# Devise for authentication
gem "devise"

# Redis adapter for Action Cable (optional)
# gem "redis", ">= 4.0.1"

# Kredis for higher-level Redis data types (optional)
# gem "kredis"

# Active Model has_secure_password
# gem "bcrypt", "~> 3.1.7"

# Timezone data for Windows
gem "tzinfo-data", platforms: %i[ mswin mswin64 mingw x64_mingw ]

# Reduce boot time via caching
gem "bootsnap", require: false

# Image processing (optional)
# gem "image_processing", "~> 1.2"

# Hotwire Rails meta-gem (optional, you already have turbo/stimulus)
gem "hotwire-rails", "~> 0.1.3"

# dry-rb ecosystem
gem "dry-monads"       # Monads and functional programming helpers
gem "dry-struct"       # Immutable data structures (optional)

group :development, :test do
  # Debugging for Rails
  gem "debug", platforms: %i[ mri mswin mswin64 mingw x64_mingw ], require: "debug/prelude"

  # Security static analysis
  gem "brakeman", require: false

  # Ruby style guide with Rails defaults
  gem "rubocop-rails-omakase", require: false

  # RSpec for testing
  gem "rspec-rails"
end

group :development do
  # Rails console on error pages
  gem "web-console"

  # Highlight errors in terminal
  gem "error_highlight", ">= 0.4.0", platforms: [ :ruby ]
end

group :test do
  # System testing
  gem "capybara"
  gem "selenium-webdriver"

  # Factories for test data
  gem "factory_bot_rails"

  # Randomized test data
  gem "faker"
end
