# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

# gem "decidim", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "fix/wizard-create-step-cookie_overflow"
# gem "decidim", path: "../decidim"

# gem "decidim-consultations", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "0.12-stable"
# gem "decidim-initiatives", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "0.12-stable"

# gem "decidim-consultations", path: "../decidim"
# gem "decidim-initiatives", path: "../decidim"

# gem "decidim-participations", git: "https://github.com/OpenSourcePolitics/decidim-participations.git", branch: "09-stable"
# gem "decidim-export", git: "https://github.com/OpenSourcePolitics/decidim-user-export.git"

gem "bootsnap", "~> 1.3"

gem "puma", "~> 3.0"
gem "uglifier", "~> 4.1"

gem "faker", "~> 1.8"

gem "ruby-progressbar"
gem 'sentry-raven'

group :development, :test do
  gem "byebug", "~> 10.0", platform: :mri

  gem "decidim-dev", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "fix/wizard-create-step-cookie_overflow"
  # gem "decidim-dev", path: "../decidim"
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

group :production do
  gem 'passenger'
  gem 'fog-aws'
  gem 'dalli'
  gem 'sendgrid-ruby'
  gem 'newrelic_rpm'
  gem 'lograge'
  gem 'sidekiq'
end
