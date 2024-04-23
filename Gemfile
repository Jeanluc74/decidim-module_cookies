# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", git: "https://github.com/decidim/decidim", branch: "release/0.25-stable"
gem "decidim-cookies", path: "."

gem "bootsnap"
gem "deepl-rb"

gem "puma"
gem "uglifier"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri

  gem "decidim-dev", git: "https://github.com/decidim/decidim", branch: "release/0.25-stable"
end

group :development do
  gem "faker"
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring"
  gem "spring-watcher-listen"
  gem "web-console", "~> 3.5"
end
