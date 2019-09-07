source "https://rubygems.org"

gem "jekyll"

group :jekyll_plugins do
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
end

gem "wdm", :install_if => Gem.win_platform?
